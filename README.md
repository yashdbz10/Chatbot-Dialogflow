# Chatbot-Rasa
Step-1: create new folder with name rasa

Step-2: open that folder in pycharm

Step-3: now create new env in pycharm by file>setting>project name>python interpeter> setting>add new> now select new enc with coda and pytohn version 3.6

Step-4: now in the terminal activate your env and run these commands one by one in sequence

Step-5: pip install rasa-x==0.32.2 --extra-index-url https://pypi.rasa.com/simple

Step-6: pip install spacy

Step-7: python -m spacy download en

Step-8: python -m spacy download en_core_web_md

Step-9: python -m spacy link en_core_web_md en

Step-10: rasa init

Step-11: rasa shell (for starting chatbot in the terminal itself)

Step-12: rasa x (for starting chatbot in the browser)

Step-13: rasa train (after adding new intents to train rasa again use this command and use above commands to again run the chatbot)
