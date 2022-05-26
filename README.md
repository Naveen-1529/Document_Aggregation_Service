## Document-aggregation-service

### About the service

The document-aggregation-service handles all the operations related to Box file management. This comes into role as soon as the document is uploaded in toorak platform. It handles Box related activities such as reading documents and creating conditions from the DD reports. It copies files from AWS S3 bucket to Box and Vice versa and similarly keeps Sync between AWS S3 bucket and Box files.


### Getting Started
---------------
Kindly follow below instructions for setting up your project locally. To get a local copy up and running follow these simple example steps.

### Prerequisites

- Install pyramid
```
    pip install pyramid
```

### Installation
- Clone the repo :
```
    https://github.com/Toorak-Capital/document-aggregation-service.git
```

### Steps to be followed after cloning

- Change directory into your newly created project.
```
    cd document-aggregation
```

- Create a Python virtual environment.
```
    python3 -m venv env
```

- Upgrade packaging tools.
```
    env/bin/pip install --upgrade pip setuptools        
```

- Install the project in editable mode with its testing requirements. During this installation github will ask for authentication several times. Kindly provide authentication for the same.
```
    env/bin/pip install -e ".[testing]"                 
```


- Run your project's tests.
  ```
    env/bin/pytest                                    
  ```

- Run your project.
  ```
    env/bin/pserve development.ini                       
  ```

**_NOTE:_**  The above commands are applicable for Mac. For windows one will have to replace 'bin' with 'Scripts'.<br /> 
Example- env/Scripts/pserve development.ini
