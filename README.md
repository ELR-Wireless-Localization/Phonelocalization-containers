# Phonelocalization

User Guide : Contains necessary details and information about the project and tools required to install.

PPT: Consists of all weekly update

MyProject folder contains below files:
1. Data Collection
    1.1 data_collection.py
    1.2 Dockerfile
    1.3 requirements.txt
2. Inference
    2.1 inference.py
    2.2 Dockerfile
    2.3 requirements.txt
4. Preprocessing
    3.1 preprocessing.py
    3.2 Dockerfile
    3.3 requirements.txt
6. Database
   Dockerfile
requirements.txt
Docker-compose.yml

Deployment Instructions:
1. Running Docker Containers
   - The docker engine should be installed on the server, if not install that first. More information can be found on the docker website: https://docs.docker.com/desktop/install/linux-install/.
   - Run "docker-compose up --build" to start the server.
   - To shutdown the server, or recompile new code, Ctrl+C to shutdown the server.
   - Then repeat process if to start and launch server.
