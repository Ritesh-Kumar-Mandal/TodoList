# To Do
An app to help you stay organized and manage your day-to-day.

This repository uses [FastAPI](https://fastapi.tiangolo.com) for creating APIs & [Jinja2](https://pypi.org/project/Jinja2/) for creaeting and using the HTML templates and [SqlAlchemy](https://docs.sqlalchemy.org/en/14/dialects/sqlite.html) Python sql database library to maintain the CRUD operation's data.

## Installtion

```sh
git clone https://github.com/Ritesh-Kumar-Mandal/TodoList.git
cd TodoList
py -m venv venv 
source venv/Scripts/activate 
pip3 install -r requirements.txt
uvicorn main:app --reload
```
## SwaggerUI
![SwaggerUI](https://github.com/Ritesh-Kumar-Mandal/TodoList/blob/3b5147a69be95fe2277d88f89f6832766b026b54/screenshots/SwaggerUI.png)
This is how the Swagger UI for the App appears.

## HomePage
![HomePage](https://github.com/Ritesh-Kumar-Mandal/TodoList/blob/3b5147a69be95fe2277d88f89f6832766b026b54/screenshots/HomePage.png)
The Home page of the TODO app.

## Add to List
![Add](https://github.com/Ritesh-Kumar-Mandal/TodoList/blob/3b5147a69be95fe2277d88f89f6832766b026b54/screenshots/Add.png)
To add to the list of things to do. Enter the Task in the input text field, then click ADD or press enter.


## Update in List
![Update](https://github.com/Ritesh-Kumar-Mandal/TodoList/blob/3b5147a69be95fe2277d88f89f6832766b026b54/screenshots/Update.png)
Click on update to change the status of the listed tasks to completed.

## Delete from List
![Delete1](https://github.com/Ritesh-Kumar-Mandal/TodoList/blob/3b5147a69be95fe2277d88f89f6832766b026b54/screenshots/Delete.png)
![Delete2](https://github.com/Ritesh-Kumar-Mandal/TodoList/blob/3b5147a69be95fe2277d88f89f6832766b026b54/screenshots/AfterDelete.png)
To delete a task, click the delete button, and the task will be deleted.