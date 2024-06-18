##Admin System Backend
##Overview
This project is a backend system developed using Django to manage various administrative tasks, such as organizing medical certificates for access and handling assignment extensions and waivers efficiently. APIs are utilized to integrate the backend with frontend components seamlessly.

##Features
Medical Certificates Management: Organize and manage medical certificates.
Assignment Extensions: Handle requests for assignment extensions.
Waiver Management: Manage assignment waivers.
API Integration: Seamless integration between backend and frontend via APIs.

##Installation
Clone the repository:

git clone https://github.com/yourusername/admin-system-backend.git
cd admin-system-backend
Create a virtual environment:

python3 -m venv venv
source venv/bin/activate
Install dependencies:

pip install -r requirements.txt
Run database migrations:

python manage.py migrate
Create a superuser:

python manage.py createsuperuser
Start the development server:

python manage.py runserver
