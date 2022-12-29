# To Do
An app to help you stay organized and manage your day-to-day.

This repository uses [FastAPI](https://fastapi.tiangolo.com) for creating APIs & [Jinja2](https://pypi.org/project/Jinja2/) for creaeting and using the HTML templates and [SqlAlchemy](https://docs.sqlalchemy.org/en/14/dialects/sqlite.html) Python sql database library to maintain the CRUD operation's data.

To access the Swagger UI for the application, click on the URL. https://todoapp.herokuapp.com/docs

## Installtion

```sh
git clone https://github.com/Ritesh-Kumar-Mandal/Auth.git
cd Auth
py -m venv venv 
source venv/Scripts/activate 
pip3 install -r requirements.txt
uvicorn main:app --reload
```

## HomePage
![Auth](https://github.com/Ritesh-Kumar-Mandal/Lifeopedia/blob/53e358a20d766f08c4579d92d1aa20f5c9c099b9/ScreenShots/APIs/admin-controls.png)

## Add to List
![Admin](https://github.com/Ritesh-Kumar-Mandal/Lifeopedia/blob/53e358a20d766f08c4579d92d1aa20f5c9c099b9/ScreenShots/APIs/auth.png)

## Update in List
![User](https://github.com/Ritesh-Kumar-Mandal/Lifeopedia/blob/dfd49d2479ab902a81820249f2da12702e9dc0fb/ScreenShots/APIs/user-controls.png)
Users have less CRUD control than administrators. The current user can view, change or update his or her own information, which is stored in the database.

## Delete from List
After entering the correct login credentials, the user will receive a JSON Web Token that will be valid for an hour or until the user logs out.
