# Django Channels Example

## Install

    python3.6 -m venv .venv
    . .venv/bin/activate
    pip install -r requirements.txt

    cd apps/
    ./manage.py migrate
    ./manage.py runserver

Then visit:

<http://localhost:8000/chat/lobby/>


## Install Redis on Mac

    brew install redis
    redis-server /usr/local/etc/redis.conf
