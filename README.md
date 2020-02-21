# Overview
This application helps the user to Read,Create,Delete,Update the Blog post,The app uses django for the server side and React for the client side of the application.

# Backend-Setup

Activate Vitual env and install dependencies!

Make Migrations:-
```
./manage.py makemigrations
./manage.py migrate
```
Start server for your REST-API:-
```
./manage.py runserver
```
# Frontend Setup:-
Go to root and Open another terminal window
```
cd Frontend
```
Install Dependencies:-
```
npm install
```
Run Server:-
```
npm run dev
```

So apparently to server is running one is localhost:8000(clientside react) and second is localhost:8080(django-api) So to see live application open http://localhost:8000 in your browser window
