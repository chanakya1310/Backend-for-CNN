# Backend-for-CNN
Learning how to create backend for a simple CNN (Cat or Dog) using FastAPI

In order to run on local machine:

1. Clone the Repo

2. 'cd' into the cloned Repo

3. Install the required packages mentioned in requirements.txt using:

        pip3 install -r requirements.txt
        
4. Run main.py using:
    
        python3 main.py
 

To view the docs when the server is on or after running main.py:

http://127.0.0.1:8000/docs
 

Sample Response:

i).When the uploaded photo is of a dog or a cat.

    {
      "Dog Percentage": 100,
      "Cat Percentage": 0,
      "Label": "Dog"
    }

ii).When the uploaded file is not of jpg or png format.

    {
      "Error": "Image must be of jpg or png format!"
    }
