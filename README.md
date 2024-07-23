# recipe-app-api
This Django web application focuses on creating an advanced recipe API that allows users to upload and store their favorite recipes from photos and the web. Users can create recipes with titles, price points, cooking times, ingredients, and tags like "comfort food," "vegan," or "dessert." Think of it as a virtual recipe box.

## Getting Started

To run this project on your local machine, follow these steps:

### Prerequisites

- Python 3.8 or higher
- Docker and Docker-Compose installed (Note: Docker cannot run on Windows 10 Home edition. Windows 10 Pro or Enterprise is required to use Hyper-V, which Docker uses for virtualization.)
- Git installed
- PostgreSQL database

### Setup

1. Clone the repository.
2. Setup Docker and Docker-Compose
3. Run the app with:
  ```bash
  docker-compose up -d

### Usage

- Open a web browser and navigate to http://127.0.0.1:8000/.
- Register a new account or log in with an existing one.
- Explore the features of the API, such as user authentication, creating and managing recipes, and uploading images.

### Technical Specifications

- Security: Secure user authentication and password management.
- Scalability: Built with Docker for easy scaling and deployment.
- Testing: Comprehensive unit tests ensuring code reliability.
- CI/CD: Integrated CI/CD pipeline using GitHub Actions for automated testing and deployment.
- Database: Utilizes Postgres for robust and efficient data management.

