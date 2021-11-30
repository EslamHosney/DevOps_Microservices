# Test Git

FROM python:3.7.3-stretch

# working directory
WORKDIR /app

#copy source code to working directory

COPY . flask_app/web.py /app/

# install packages

RUN pip install --upgrade pip &&\
    pip install --trusted-host pypi.python.org -r requirements.txt
    
    
EXPOSE 80


CMD ["python", "web.py"]