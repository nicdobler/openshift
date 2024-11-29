FROM python:alpine
RUN pip install Redis requests
COPY worker.py .
CMD python worker.py
