NLP Course Project - Building a Chatbot
---------------------------------------

1. Credentials used in the project:

For Zomato : zomato_api_key = "fefc969ce30fd4d5331765cfcaf8a59d"
For Gmail  : username=foodie.chatbot.ml11,password=f00d1eb0t (foodie.chatbot.ml11@gmail.com)


2. Setup requirements:
Module versions are listed in requirements.txt file.

Major modules also listed as below:

matplotlib==3.1.3
numpy==1.18.3
rasa==1.9.6
rasa-nlu==0.15.1
rasa-sdk==1.9.0
rasa-x==0.27.5
scikit-learn==0.22.2.post1
scipy==1.4.1
sklearn-crfsuite==0.3.6
spacy==2.1.9
tensorboard==2.1.1
tensorflow==2.1.0
tensorflow-addons==0.9.1
tensorflow-estimator==2.1.0
tensorflow-hub==0.7.0
tensorflow-probability==0.7.0

Others: 
Microsoft Visual Studio VC++ Build tools 

3. Install steps:

pip install rasa-x --extra-index-url https://pypi.rasa.com/simple
pip install rasa[spacy]
python -m spacy download en_core_web_md
python -m spacy link en_core_web_md en

4.
# For testing the NLU model, you can use the shell command of RASA: 
rasa shell
rasa run actions

# or
rasa run actions & rasa shell

