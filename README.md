## Machine_learning_Project

This is the first machine learning project

### Software and account Requirement. 

1. Github Account
2. Heroku Account
3. VS Code IDE
4. GIT cli

Creating conda environment
```
conda create -p venv python==3.7 -y
```
```
conda activate venv/
```
OR

```
conda activate venv
```

pip install -r requirements.txt

To add files to git 
```
git add .
```

OR

```
git add <file_name>
```
To check git status:
```
git status
```

Note : To ignore file or folder from git we can write name of file/folder in .gitignore file 

To create version/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github

```
git push origin main
```

To check remote url
```
git remote -v
```





Git commands :

```
https://git-scm.com/docs/gittutorial
```

To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = iyswaryasaradha@gmail.comHEROKU_
2. HEROKU_API_Key = 61b3f178-76a8-419e-8077-8b8d1387d7fa
3. HEROKU_APP_NAME = firstmldeployment

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```

> Note: Image name for docker must be lowercase

To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 f8c749e73678
```

To check running container in docker
```
docker ps
```
Tos stop docker conatiner
```
docker stop <container_id>
```
