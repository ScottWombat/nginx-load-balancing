FROM python:3.11.1-alpine3.17
# Install dependencies:
COPY requirements.txt .
RUN pip install -r requirements.txt
EXPOSE 3002
COPY app.py .
# Run the application:
CMD python3 app.py