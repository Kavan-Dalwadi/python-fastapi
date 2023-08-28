FROM python:3.8.10
WORKDIR /my-app
COPY ./requirements.txt ./
RUN pip install -r ./requirements.txt
COPY . .
EXPOSE 8000
CMD ["uvicorn", "--reload", "main:app"]