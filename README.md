# QA Engineer Assessment
**Difficulty**: Junior  
**Length**: 4 hours maximum  

## Assessment Download Link
Here is the [assessment](https://bitbucket.org/f8th/f8th-assessment/downloads/qa-engineer.zip) to download.

## Assessment Description
This repository is the code of an API built on FastAPI framework. The API has multiple endpoints with different input validations.  

How would you implement unit tests and how should we use them? Please write down code, plan, or anything that could show what you would do in this situation. Include your assumptions and instructions to run your solution in this file.  

Lastly, create a repository on GitHub or Bitbucket, upload your solution with this README.md file, then send us the repository URL by email at hr@f8th.ai. Good luck!

## How do I get set up? ###

You have two choices.
1. Docker (Recommended)
2. Local Environment

### Running the API with Docker ###

1. Go into the folder [qa-engineer](./../qa-engineer)
2. Build the docker image `docker build . -t qa-engineer-assessment`
3. Run the image `docker run -p 80:80 qa-engineer-assessment`

### Running the API on your Local Environment ###

1. Install `Python 3.7`, `fastapi` and everything listed into the file [requirements.txt](./requirements.txt)
2. Run the app `main.py` into the folder [src](./src)

### Accessing the API Documentation
When your app is running, you can access the API documentation at http://0.0.0.0/docs
