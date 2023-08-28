FROM python:3.8.10
WORKDIR /my-app
COPY ./requirements.txt ./fastapi-env/ ./
RUN source ./fastapi-env/bin/activate
COPY . .
EXPOSE 8000
CMD ["uvicorn", "--reload", "main:app"]