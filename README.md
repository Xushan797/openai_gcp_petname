# openai_gcp_petname
This is a webapp using openai and deploy on gcp  
I can use openAI API to generate dog name  

run command locally:  
python -m venv venv  
. venv/bin/activate  
pip install -r requirements.txt  
flask run  

or run command:  
Docker build -t mypet .  
Docker run -e 5000:5000 mypet  

or run command:  
python -m venv venv  
. venv/bin/activate  
make run  

or I have already deploy the service using gcp  

![image](https://user-images.githubusercontent.com/96745697/155864406-e42314cd-b0c2-4057-a7b9-8f4f698f0e40.png)

