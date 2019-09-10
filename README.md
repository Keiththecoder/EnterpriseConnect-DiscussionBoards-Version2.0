# EnterpriseConnect-DiscussionBoards-Version2.0
Fully Running Discussion Boards 

[![Python Version](https://img.shields.io/badge/python-3.6-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-1.11-brightgreen.svg)](https://djangoproject.com)



## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/Keiththecoder/EnterpriseConnect-DiscussionBoards-Version2.0.git
```

 Create a Virtual Environment in the Folder
```bash
python3 -m venv venv
```
Activate the Environment

```bash
source venv/bin/activate
```


Install the requirements:

```bash
pip install -r requirements.txt
```

Setup the local configurations:

```bash
cp .env.example .env
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.


## License

The source code is released under the [MIT License](https://github.com/sibtc/django-beginners-guide/blob/master/LICENSE).
