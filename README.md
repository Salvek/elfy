How to run:

1. Create virtual environment and activate it:

        virtualenv venv
        cd venv/bin
        source activate

2. Install dependencies by running:

        pip install -r requirements.txt


3. Run application with command when in app directory:

        flask --app app.py run


-------------------------------------------------------

How to run with Docker (pull from DockerHub):

1. Pull image from DockerHub:

        docker pull salvekk/santas-elf-menager:latest


2. Run image with docker:

        docker run salvekk/santas-elf-menager

-------------------------------------------------------

How to run with Docker (build image):

1. Build image when in /app directory with command:

        docker build -t santas-elf-menager .


2. Run image with docker:

        docker run -d -p 5000:5000 santas-elf-menager


-------------------------------------------------------


Deployment is done through DigitalOcean service:

    https://octopus-app-hg7dl.ondigitalocean.app/
