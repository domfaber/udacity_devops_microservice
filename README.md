[![CircleCI](https://circleci.com/gh/domfaber/udacity_devops_microservice.svg?style=svg)](https://circleci.com/gh/domfaber/udacity_devops_microservice)

## Project Overview

With this project you can make predictions about the housing pices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on.

## Setup the Environment
1. python3 -m venv ~/.devops
2. source ~/.devops/bin/activate
3. Run `make install` to install the necessary dependencies



### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`
4. Make a prediction: `./make_prediction.sh`

Hint: Re-run the kubernetes.sh script when the pod has successfully launched. Otherwise the port will not be forwarded to localhost:8000. 
