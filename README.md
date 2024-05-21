# ECOMMERCE WEBSITE
---

### Admin
- First admin will login ( for username/password run following command in cmd )
```
python manage.py createsuperuser
```
- Give username, email, password and your admin account will be created.
- After login, there is a dashboard where admin can see how many customers are registered, how many products are there for sale, how many orders placed.
- Admin can add/delete/view/edit the products.
- Admin can view/edit/delete customer details.
- Admin can view/delete orders.
- Admin can change status of order (order is pending, confirmed, out for delivery, delivered)
- Admin can view the feedbacks sent by customers.
---

## HOW TO RUN THIS PROJECT
- Install Python(3.10) 
- Open Terminal and Execute Following Commands :
```
pip install -r requirements.txt
```
- Move to project folder in Terminal. Then run following Commands :
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settins.py file, You have to give your email and password

## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.
