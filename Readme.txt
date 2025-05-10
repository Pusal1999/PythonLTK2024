**Hướng dẫn**

- Cài đặt các yêu cầu: pip install -r requirements.txt
- Sau đó, thực hiện di chuyển cơ sở dữ liệu: python manage.py makemigrations
- python manage.py migrate
- Và cuối cùng, chạy ứng dụng: python manage.py runserver

Đối với Tài khoản quản trị, vui lòng tạo một tài khoản với superuser!

Phương thức chạy:

Setup/Installation
Download and Extract the provided source code zip file. (download button is located below)
Open your Terminal/Command Prompt window. (make sure to add "python" and "pip" in your environment variables)
Change the working directory to the extracted source code folder. i.e. cd C:\Users\Personal-23\Desktop\django_pgs
Run the following commands:
pip install -r requirements.txt
python manage.py migrate
Create a Superuser by executing the following command:
python manage.py createsuperuser
Run the project by executing the following command:
python manage.py runserver
Keep the terminals open and running.
Open a web browser and browse http://localhost:8000/ or http://127.0.0.1:8000/