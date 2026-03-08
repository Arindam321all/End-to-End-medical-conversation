# End-to-End-medical-conversation

#how to run
#step

clone the repo

bash--
project repo: https://github.com/

step-01 -> create a conda env after opening the repo

bash--
conda create -n medibot python=3.10 -y

conda activate medibot


(medibot is any name)

step-02 -> install the requirements
bash--
pip install -r requirements.txt

##create a .env file in the root directory and add Pinecone and openai credentials as follows

PINECONE_API_KEY = "XXXXXXXXXXXXxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
-----------------------------------------------------------------------------------------
#run the following commands
python store_index.py
---------------------------
python app.py
----------------------------
open up localhost:
-------------------------------
Techstack used:
   - Python
   - Langchain
   - Flask
   - GPT
   - Pinecone

