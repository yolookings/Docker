# Gunakan base image python:3.8
FROM python:3.8

# Install flask
RUN pip install flask

# Buat direktori /var/www/html
WORKDIR /var/www/html

# Salin file index.py ke dalam direktori /var/www/html
COPY ./www/index.py .

# Expose port 5003
EXPOSE 5003

CMD ["python", "index.py"]
