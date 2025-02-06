# Backorder_prediction_ML
Internship Project using Machine Learning

Requirement.

### software and account requirement.

1.[git cli](https://git-scm.com/downloads)

2.[github account](https://github.com/)

3.[Heroku account](https://id.heroku.com/login)

4.[vs code account](https://code.visualstudio.com/download)

5.[terminal](https://learn.microsoft.com/en-us/windows/terminal/install)


# Create repository in github account

# copy repository url and open it on any terminal to clone 
```
git clone "url"
```
from the perticular folder location , open vs code 
```
code .
```
# create new envirnment
```
create file : requirements.txt : Flask
pip install -r requirements.txt  

conda create -p path\\myenv
conda activate path\\myenv

 or 
pip install virtualenv
virtualenv "myenv"
myenv\scripts\activate.bat
```
 # create app : app.py
 # run app 
 ```
 flask run 
 or 
 python app.py
 ```

 # Heroku accound login

 To setup CI\CD Pipeline in heroku we need 3 information:

 1. HEROKU_EMAIL = poojaapaandey9@gmail.com
 2. HEROKU_API_KEY = HRKU-0197c56d-3222-4875-8417-83f9da674fb3
 3. HEROKU_APP_NAME = backorder-prediction-app



# Create Docker File
# Build Docker image 
```
docker build -t <image_name>: <tagname> .
```
>Note : Image name must be in small lowercase

To list docker image 
```
docker images
```
Run docker image 
```
docker run -p 5000:5000 -e PORT=5000 <image_id>
```