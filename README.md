
================ Project setup ====================

$ Install your desired python3 version 

$ Create directory where project sits and environment dir

    mkdir /var/projects && mkdir /var/envs && mkdir /var/envs/bin

$ Create virtualenv (optional)

    cd /var/envs && mkvirtualenv webcamapp --python=python3
    
$ Clone project repo

    cd /var/projects && git clone https://github.com/anisakhlian/webcamapp.git  

$ Install requirements for the project

    cd /var/projects/webcamapp && pip install -r requirements.txt

$ To run project 

    python webstreaming.py --ip 0.0.0.0 --port 8000
