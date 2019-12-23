# Devman Django ORM lesson 2

Study project study Django ORM.

## Installation

This script was developed and tested with python3.7 
But according [official documentation page](https://docs.djangoproject.com/en/3.0/faq/install/#faq-python-version-support) 
you can use another versions of python.

Before first run install essential libs.

`pip3 install -r requirements.txt`

In the root of the project create `.env` file to add Postgres credentials.

```.env
DATACENTER_PSQL_HOST=somehost.dev
DATACENTER_PSQL_PORT=Port number
DATACENTER_PSQL_NAME=Name of the database
DATACENTER_PSQL_USER=Name of the user
DATACENTER_PSQL_PASSWORD=SuperSecret Password
DATACENTER_SECRET_KEY=Your Django secret kay

DATACENTER_DEBUG=true  -- To switch on debug mode
```

You can find credentials at the [first task](https://dvmn.org/modules/django-orm/lesson/watching-storage/#1) of lesson.

## Usage

Just run this command in terminal
```bash
python manage.py runserver 8000
```
and copy-paste link from terminal to browser.

## License

MIT License

Copyright (c) 2019 Roman Kazakov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.