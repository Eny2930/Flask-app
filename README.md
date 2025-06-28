# Flask App

A simple Flask web application with CI/CD pipeline using GitHub Actions.

## 🚀 Features

- Flask web framework
- GitHub Actions CI/CD pipeline
- Docker containerization support
- SSH-based Git authentication

## 📋 Prerequisites

- Python 3.7+
- Docker (optional, for containerization)
- Git

## 🛠️ Installation

### Clone the Repository
```bash
git clone git@github.com:Eny2930/flask-app.git
cd flask-app
```

### Create Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## 🏃‍♂️ Running the Application

### Local Development
```bash
python app.py
```

The application will be available at `http://localhost:5000`

### Using Docker
```bash
# Build the image
docker build -t flask-app .

# Run the container
docker run -p 5000:5000 flask-app
```

## 📁 Project Structure

```
flask-app/
├── .github/
│   └── workflows/
│       └── ci.yml          # GitHub Actions workflow
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
├── Dockerfile             # Docker configuration
└── README.md              # Project documentation
```

## 🔧 Development

### Adding New Features
1. Create a new branch: `git checkout -b feature-name`
2. Make your changes
3. Commit: `git commit -m "Add new feature"`
4. Push: `git push origin feature-name`
5. Create a Pull Request

### Environment Variables
Create a `.env` file for local development:
```bash
FLASK_ENV=development
FLASK_DEBUG=True
```

## 🚀 Deployment

### GitHub Actions
The project includes a CI/CD pipeline that automatically:
- Builds a Docker image on every push to master
- Runs tests (if configured)
- Deploys to production (if configured)

### Manual Deployment
1. Build the Docker image: `docker build -t flask-app .`
2. Deploy to your preferred platform (Heroku, AWS, etc.)

## 🧪 Testing

```bash
# Install test dependencies
pip install pytest

# Run tests
pytest
```

## 📝 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /        | Home page   |

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Bryan** - [bryan.ene@outlook.com](mailto:bryan.ene@outlook.com)

## 🙏 Acknowledgments

- Flask framework
- GitHub Actions for CI/CD
- Docker for containerization

## 📞 Support

If you have any questions or run into issues, please open an issue on GitHub or contact the author.

⭐ Star this repository if you found it helpful!

## 📞 Support

If you have any questions or run into issues, please open an issue on GitHub or contact the author.

⭐ Star this repository if you found it helpful!
