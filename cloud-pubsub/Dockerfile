FROM python:3.13.0rc2-slim
COPY . .
RUN pip install -r requirements.txt
ENTRYPOINT ["python", "-u", "main.py"]
