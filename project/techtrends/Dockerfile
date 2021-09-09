FROM python:2.7
LABEL maintainer = "Barhome"
COPY . /app
WORKDIR /app
RUN pip install -r requirments.txt
CMD ["python","app.py"]
EXPOSE 3111
