# nlp course_stuff
store my online courses code


## Reproduce stackoverflow chatbot
- ssh into the ec2 machine
- cd into project folder
- open a tmux session
- run docker image by: docker run -it -p 8080:8080 --name coursera-aml-nlp -v $PWD:/root/coursera akashin/coursera-aml-nlp
- cd into coursera folder
- uninstall scikit-learn
- install scikit-learn==0.22.2.post1
- run main_bot.py with token = 1139378077:AAHsKLpsd7N2Ho9XKAo7ztWt5cMftpTzuss
- Cntrl + b, d
- close ssh connection
