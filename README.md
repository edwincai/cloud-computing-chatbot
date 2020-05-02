# cloud-computing-chatbot
Cloud computing project. It is a chatbot that can chat with users through analyzing the sentences.More specifically, we made it as a medical assistant for a hospital.



### Technology

The chatbot is based on tornado(<https://www.tornadoweb.org/en/stable/>) and bootstrap(<https://getbootstrap.com/>)

The deep learning training is based on keras and nltk. You can find a pre-trained model in data folder or you can train by yourself using train_chatbot.py



### Deployment guidance on AWS ec2 instance

1. Create a new EC2 instance on AWS, choosing the Ubuntu 18 system.
2. Git clone this repository to your instance using SSH.
3. Configure python environment for running this project: python3-pip, python-tornado, tensorflow, keras, ntlk, ntlk.wordnet, ntlk.punkt
4. Run the chatdemo.py
5. Now you can visit the web application using the public IP of your ec2 instance, with port 8080.