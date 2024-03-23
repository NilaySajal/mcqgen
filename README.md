# MCQ generator from Text

## Steps to deploy the web application

1) first log in to the AWS: [https://aws.amazon.com/console/](https://aws.amazon.com/console/)

2) Search about the EC2

3) You need to configure the UBUNTU machine

4) Launch the instance

5) Update the Machine :

sudo apt update

sudo apt-get update

sudo apt upgrade -y 

sudo apt install git curl unzip tar make sudo wim wget -y

git clone 'your repository'

sudo apt install python3-pip

pip3 install -r requirements.txt

python3 -m streamlit run StreamlitAPP.py

If you want to add open ai api key

1. create .env file in your server using touch .env

2. Then fire the command vi .env to edit the .env file

3. Press i for inserting text into the file and write your open ai api key

4. Press esc to save and execute :wq to exit

5. Go to the security settings and add the inbound rule

6. Add the port 8501.