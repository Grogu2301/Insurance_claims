
## End to End ML Project

## Please find the App here : - 

https://gbiamgaurav-insurance-claims-app-yflzbx.streamlit.app/



[Check the data source](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4954928053318020/1058911316420443/167703932442645/latest.html)


1. Create environment

`conda create -p venv python==3.8 -y`

2. Activate environment

`conda activate venv/`

2. Install dependencies

`pip install -r requirements.txt`

3. Run the app

`streamlit run app.py`


<<<<<<< HEAD
<<<<<<< HEAD
Workflow to be followed : 

1. Update the components/class

2. Update the utils/to save custom functions

3. Update data_ingestion.py to finally run


## Find the app here:
=======
## Create Docker image
>>>>>>> d46bb5d76f9659668df29f4b01cd2a2bc3f70db7

https://grogu2301-insurance-claims-app-o1or4k.streamlit.app/

AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
AWS_REGION
AWS_ECR_LOGIN_URI
=======
## Run the commands

`sudo apt-get update -y`

`sudo apt-get upgrade`

`curl -fsSL https://get.docker.com -o get-docker.sh`

`sudo sh get-docker.sh`

`sudo usermod -aG docker ubuntu`

`newgrp docker`

`docker --version`


## Add the secrets 

AWS_ACCESS_KEY_ID

AWS_SECRET_ACCESS_KEY

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = "331777385192.dkr.ecr.us-east-1.amazonaws.com"

>>>>>>> adbe5967711dc03cdfec4859cefb8e9aa622c6e5
ECR_REPOSITORY_NAME