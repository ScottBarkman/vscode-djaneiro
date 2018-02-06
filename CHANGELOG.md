# Change Log
All notable changes to the "vscode-djaneiro" extension will be documented in this file.

## [1.4.0]

### snippets/admin

**_rename fieldsets.json to options.json_**

+ **classes**:

    - added ModelAdmin, StackedInline, TabularInline from views/views.json

    - added SimpleListFilter (simplelistfilter)
    
+ **imports**:
    - added Adminsite (iadminsite)



### snippets/models

+ **classes**:

    - added choose \_\_str\_\_ or \_\_unicode\_\_: Model and Model_full.

    - added manager (mngr) and queryset\_from\_manager (qs_mngr).

![model_full](https://github.com/klavman/vscode-djaneiro/blob/master/images/model_full.gif "model_full")
    
    
+ **fields**:

    - updated all short descriptions.

    - added Django version number when field was new or deprecated.

    - added on\_delete in fk and o2o: 

        > "will become a required argument in Django 2.0. In older versions it defaults to CASCADE."

    - added PostgreSQL specific model fields: HStoreField, JSONField and ArrayField

    - added which field depends on an external package: e.g. PhoneNumberField
    
+ **imports**:

    - added decorator for forwards compatibility python_2_unicode_compatible (iuc).

    - added PostgreSQL specific model fields (ipostgresmf).

    - added signals. (isignals)

    - removed (irmf) is a external package from django-wysiwyg-redactor

![isignals](https://github.com/klavman/vscode-djaneiro/blob/master/images/isignals.gif "isignals")
    
    
+ **methods**:

    - added receiver function for signals. (receiver)


### snippets/python

+ python:
    - added unicode_literals (iul)


### snippets/urls

+ **imports**:

    - added functions (path, re_path...) for use in URLconfs: Django 2.0  (iurls)

    - added django.conf.urls for Django version <= 1.11 and Django version >=2.0 (iconf_urls)

        * https://docs.djangoproject.com/en/1.11/ref/urls/

        * https://docs.djangoproject.com/en/2.0/ref/urls/

![django_urls](https://github.com/klavman/vscode-djaneiro/blob/master/images/django_urls.png "django_urls")
        
![reverse](https://github.com/klavman/vscode-djaneiro/blob/master/images/reverse.gif "reverse")

+ **methods**:
        - added url() and path() inline and stacked.

![urlpatterns](https://github.com/klavman/vscode-djaneiro/blob/master/images/urlpatterns.gif "urlpatterns")
        

+ **regexes**:
        - added Username

### snippets/forms

**_added methods.json_**


+ **fields**:

    - added PostgreSQL specific form fields: HStoreField, JSONField and ArrayField 
    
+ **imports**:

    - added PostgreSQL specific model fields (ipostgresff).  

+ **methods**:

    - added clean_data.



### snippets/views
**_views.json split -> classes.json and methods.json_**

+ **imports**:

    - regroup generic CBVs (igenericviews)

    - added (isettings) from settings/imports.json


### Others

- Update Readme

- Update package.json

## [1.3.0]

Added moar python and django template support (Thanks sebastian-code & supadrupa! )

## [1.2.0]

Change docstrings to class definitions for flake8 compatibility
Updated model / form fields to utilize fields in Django 1.11
Clean up repo from initial sublime port

## [1.1.6]
- Fix admin inline spacing
- Change from double quotes to single quotes in template tags
- New logo

## [1.0.1]
- Extension cleanup, setup repo for pull requests

## [1.0.0]
- Initial release
