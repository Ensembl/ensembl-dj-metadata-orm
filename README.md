Ensembl Metadata ORM layer reusable app
=======================================

Allow easy db layer access to Ensembl Metadata database
 integration in any already existing Django Application
 
Quick start
-----------

1. Add "metadata_orm" to your INSTALLED_APPS setting like this::

```
   INSTALLED_APPS = [
       ...
       'metadata_orm',
   ]
```

2. Run ``python manage.py migrate`` to create the metadata models if you don't have a database ready
