# Your Trading Journal Dockerized

Same project:
https://github.com/AndyMelm/django_redux_project

But for docker users.
## Prerequisites

- Docker 

## Usage

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/AndyMelm/project_dockerized.git
   ```

2. Navigate to the project directory:
```
cd project_dockerized
```

3. Create a .env file in the project root directory with the following environment variables and their values:
```
SECRET_KEY=your_secret_key

EMAIL_HOST=smtp.elasticemail.com
EMAIL_PORT=your_email_port
EMAIL_HOST_USER=your_email_host_user
EMAIL_HOST_PASSWORD=your_email_host_password
EMAIL_USE_TLS=True
DEFAULT_FROM_EMAIL=your_default_from_email

api_key_converter=your_api_key
```
Replace placeholders with your actual configuration values.

4. Run the following command to start the project containers: (Ensure Docker is running before executing docker-compose commands.)
```
docker-compose up 
```

5. Access the frontend application in your web browser at http://localhost:3000.

6. To stop the containers, run:
```
docker-compose down
```
