FROM python:3.6.8
 
COPY . .
 
# run pip dependencies
#Unsure what is meant by this
RUN pip3 install -r requirements.txt
 
EXPOSE 5000

ENTRYPOINT ["/usr/local/bin/python3", "app.py"]