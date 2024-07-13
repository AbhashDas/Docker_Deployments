# Docker_Deployments

Task1:
- design a docker-compose.yml file to deploy wordpress application using wordpress image deploying at 8000 and mysql server image at 3306.
- My host port was changed to 3307 because 3306 was occupied.
- Go to localhost:8000 to launch the application.

Task2:
- Add .env file with port details and mongodb url(created while deploying docker-compose.yml file using mongo and mongo-express image) in both auth and Streaming service.
- write Dockerfiles for backend - auth and streaming service and expose them at port 3001 and 3002 respectively.
- Write Dockerfile for Frontend and expose it at port-3000
- Write docker-compose.yml file to deploy both the backend and frontend services one by one along with mongodb containerized using mongo and mongodb container images.
- use docker-compose build to build the file.
- use docker-compose up to create container services
- go to localhost:3000 to launch the streaming service.
- Attached the architecture diagram.
