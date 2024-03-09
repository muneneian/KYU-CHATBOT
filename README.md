# UNIVERSITY CHATBOT
The university chatbot is intended to help university stakeholders get quick responses about the University.
## Steps to install
Inorder to install the university chatbot, follow the following steps.
1. Create a conda environment by using conda create -n your-environment-name with python 3.10.x
2. Install the necessary dependenices from the requirement.txt by running pip install -r requirements.txt
3. Change the intents in the intents.json to suit your University information.
4. Delete the classes and words pk1 files and the chatmodel.h5 files.
5. Train the model with the new data in the intents.json by running python training.py in the terminal
6. To start the application run python app3.py in the terminal.

