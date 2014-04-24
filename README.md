Django NoSQL Connectors
================

A database backend, driver, and other such things such that Django objects can be used with the following NoSQL Databases:

* MongoDB
* Amazon DynamoDB
* Cassandra
* CouchDB
* Redis

This package will allow a user to implement a database with the following syntax in `settings.py`

```python
DATABASES = {
    'default':{
        # A default engine if you wish to keep one
    },
    'database_tag': {
        'ENGINE': 'django_nosql_connectors.db.backends.YOUR_DB',
        'NAME': 'YOUR DATABASE NAME',
        'USER': 'YOUR USERNAME',
        'PASSWORD': 'YOU PASSWORD',
        'HOST' : 'YOUR HOST',
        'PORT' : 'YOUR PORT',
    }
}
```

This project is currently in progress and is not guaranteed to work until otherwise specified.
