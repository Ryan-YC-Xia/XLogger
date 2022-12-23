FROM python:3.8

# Install dependencies
COPY requirements.txt .
RUN pip install -r requirements.txt

# Copy the source code into the image   
COPY . .

# Run the Django development server
# CMD ["python", "manage.py", "runserver"]
