## Base Image
FROM python:3.8-slim
## Work Directory
WORKDIR /app
## Install requirements
COPY requirements.txt .
RUN pip install -r requirements.txt
## Copy source code
COPY . .
## Expose container port
EXPOSE 5001
## Execute Application
CMD [ "python","app.py" ]