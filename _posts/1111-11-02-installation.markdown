---
layout: post
title:  "Installation"
tag: Getting Started
permalink: IU-Alumni-Static-Site-Generated-Documentation/installation
---
### Installing frontend
1. Open a shell/command line in this folder
2. To install all packages (local to the repo) using
```npm install```
3. To build the project for production
```npm run build```
4. To start the project on development
```npm start```

### Installing backend

#### Using Python
1. Open a shell/command line in this folder (better if it was after activating a python virtual env)
2. Install the needed python packages

   ```pip install -r requirements.txt```

3. Run the python script:

    ```python3 main.py```

#### Using Docker
1. Here the image tag name is alumni-backend you can name it as you like
2. Also the port in docker is 8000 by default and locally you can map it to anything as you like
```
docker build -t alumni-backend
docker run -p 8000:8000 -d alumni-backend
```