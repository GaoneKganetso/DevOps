FROM python:alpine3.10 
# base Image 
WORKDIR /app 
#COPY . /app 
COPY requirements.txt /app/requirements.txt
# current directory
RUN pip install -r requirements.txt
EXPOSE 5000
CMD python ./launch.py

#COPY requirements.txt /app/requirements.txt
#ENTRYPOINT ["python", "./launch.py"]
