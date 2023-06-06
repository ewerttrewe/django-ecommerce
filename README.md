![GitHub last commit](https://img.shields.io/github/last-commit/ewerttrewe/django-ecommerce) ![Maintenance](https://img.shields.io/maintenance/no/2022) 
# Django Ecommerce App
> **Ecommerce site with implemented payment options via paypal for logged in and not logged in users (tracked by cookies)- django project, no REST API**


You need to follow few steps below in order to use this app on your local machine:<br><br>
1. Clone the repository using `git clone https://github.com/ewerttrewe/django-ecommerce.git` command.<br>
2. Cd to the root directory of the project on your machine and fetch and merge all the latest changes using `git pull` command.<br>
3. After that create virtual environment in your root directory via `python -m venv env` command.<br>
4. Cd to previously created environment and activate environment:<br><br>
  Actiavte virtual environment by typing in<br><br>
  &nbsp; **Windows Users:**<br>
  `.\Scripts\Activate.ps1`<br><br>
  &nbsp; **Linux/macOS Users:**<br>
  `source venv/bin/activate`<br><br>
5. cd back via `cd ..` and `pip install -r requirements.txt`<br>
6. To start the server and be able to connect to certain endpoint type in `python manage.py runserver 8000`<br>
7. Open web browser and try to connect to `http://localhost:8000`<br>
8. Now you should be able to test UI and add products to the cart, you can try to checkout and pay for something using PayPal, you can create - [PayPal Sandbox For Developers](https://developer.paypal.com/home) in order to mimic the real transaction.<br><br>


> **Disclaimer:** You can open a Python shell within the project's directory and run the following command to generate a new secret key and add it to `settings.py`, at the top level there is `SECRET_KEY=''` empty variable:<br>
`python manage.py shell`<br>
`from django.core.management.utils import get_random_secret_key`<br>
`get_random_secret_key()`<br><br>

https://user-images.githubusercontent.com/93892998/209131491-d3e78d61-7a19-475c-b3aa-f55ff00a8148.mp4

