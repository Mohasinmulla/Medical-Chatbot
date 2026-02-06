first install packages to get your personal files in code 

pip install python-dotenv

sample code for that :

from dotenv import load_dotenv
import os

load_dotenv()  # loads .env file

API_KEY_IN_CODE = os.getenv("API_KEY") // getting api key which is safely stored in your .env 
