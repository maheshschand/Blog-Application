# Blog Application

Blog Application created using Django framewok

## Features
- Creating, editing, deleting a blog post.
- Pagination to lists.
- Tags for Posts.
- Administration site for managing posts and users.
- Sharing posts by email.
- Commenting on posts.
- Retrieving Similar Posts.
- Markdown support for editing the post content.

## Demo
[Suven Blog](https://suvenblog.herokuapp.com/)

## Run project locally
1. Clone the project  
    ```bash
    git clone https://github.com/maheshschand/Blog-Application.git 
    ```
2. Create a virtual evironment
    ```bash
    python -m venv venv
    ```
3. Activate your virtual environment  
    **For Windows**
    ```powershell
    cd venv\Scripts
    activate
    ```

    **For linux**
    ```bash
    source venv/bin/activate
    ```
    The shell prompt will include the name of the active virtual environment enclosed in parentheses, as follows:
    ```bash
    (venv) $
    ```
4. Locate the Blog-Application folder and run the following command
    ```bash
    (venv) $ pip install -r requirements.txt
    ```
5. Migrate the database
    Run the following command to migrate the database.
    ```bash
    (venv) $ python manage.py migrate
    ```
6. Create a administrator account
    Run the following command to create a super user
    ```bash
    (venv) $ python manage.py createsuperuser
    ``` 
7. Run the development server
    Run the following command to turn on the development server
    ```bash
    (venv) $ python manage.py runserver
    ```
    Enter in the browser: http://127.0.0.1:8000

