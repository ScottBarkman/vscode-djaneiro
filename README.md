# Django snippets for Visual Studio Code
A collection of snippets for django templates, models, views, fields & forms. Quit typing so much, will ya?

Initially ported to vscode from [Djaneiro for Sublime Text 2/3](https://github.com/squ1b3r/Djaneiro)

If you'd like to contribute to this collection of snippets, feel free to [submit a pull request on github](https://github.com/ScottBarkman/vscode-djaneiro)

## Features

### Snippets for Django Admin

|   Abbreviation   |  Type  |               Code - Description               |
| ---------------- | ------ | ---------------------------------------------- |
| adminview        | class  | ``Model Admin with options``                   |
| stackedinline    | class  | ``StackedInline with options``                 |
| tabularinline    | class  | ``TabularInline with options``                 |
| simplelistfilter | class  | ``SimpleListFilter``                           |
| iadmin           | import | ``from django.contrib import admin``           |
| iadminsite       | import | ``from django.contrib.admin import AdminSite`` |
| register         | method | ``admin.site.register(<Model>)``               |
| registermadmin   | method | ``admin.site.register(<Model>, <ModelAdmin>)`` |
| fieldsets        | option | ``For more complex layout in ModelAdmin``      |

### Snippets for Django Form 

|  Abbreviation  |  Type  |                        Code - Description                         |
| -------------- | ------ | ----------------------------------------------------------------- |
| Form           | class  | ``Form(with TODOs)``                                              |
| ModelForm      | class  | ``ModelFom``                                                      |
| fbool          | field  | ``forms.BooleanField()``                                          |
| fchar          | field  | ``forms.CharField()``                                             |
| fchoice        | field  | ``forms.ChoiceField()``                                           |
| fcombo         | field  | ``forms.ComboField()``                                            |
| fdate          | field  | ``forms.DateField()``                                             |
| fdatetime      | field  | ``forms.DateTime()``                                              |
| fdecimal       | field  | ``forms.DecimalField()``                                          |
| fduration      | field  | ``forms.DurationField()``                                         |
| femail         | field  | ``forms.EmailField()``                                            |
| ffile          | field  | ``forms.FileField()``                                             |
| ffilepath      | field  | ``forms.FilePathField()``                                         |
| ffloat         | field  | ``forms.FloatField()``                                            |
| fimg           | field  | ``forms.ImageField()``                                            |
| fint           | field  | ``forms.IntegerField()``                                          |
| fip            | field  | ``forms.IPAddressField() - deprecated since version 1.7 ``        |
| fgenericip     | field  | ``forms.GenericIPAddressField()``                                 |
| fmochoice      | field  | ``forms.ModelChoiceField()``                                      |
| fmomuchoice    | field  | ``forms.ModelMultipleChoiceField()``                              |
| fmuchoice      | field  | ``forms.MultipleChoiceField()``                                   |
| ftypedmuchoice | field  | ``forms.TypedMultipleChoiceField()``                              |
| fmuval         | field  | ``forms.MultipleValueField()``                                    |
| fnullbool      | field  | ``forms.NullBooleanField()``                                      |
| fregex         | field  | ``forms.RegexField()``                                            |
| fslug          | field  | ``forms.SlugField()``                                             |
| fsdatetime     | field  | ``forms.SplitDateTime()``                                         |
| ftime          | field  | ``forms.TimeField()``                                             |
| ftchoice       | field  | ``forms.TypedChoiceField()``                                      |
| ftmuchoice     | field  | ``forms.TypedMultipleChoiceField()``                              |
| furl           | field  | ``forms.URLField()``                                              |
| fuuid          | field  | ``forms.UUIDField()``                                             |
| fsimplearray   | field  | ``SimpleArrayField() - PostgreSQL specific form field``           |
| fsplitarray    | field  | ``SplitArrayField() - PostgreSQL specific form field``            |
| fhstore        | field  | ``HStoreField() - PostgreSQL specific form field``                |
| fjson          | field  | ``JSONField() - PostgreSQL specific form field``                  |
| fintrange      | field  | ``IntegerRangeField() - PostgreSQL specific form field``          |
| ffloatrange    | field  | ``FloatRangeField() - PostgreSQL specific form field``            |
| fdatetimerange | field  | ``DateTimeRangeField() - PostgreSQL specific form field``         |
| fdaterange     | field  | ``DateRangeField() - PostgreSQL specific form field``             |
| ffi            | import | ``from .forms import <local_forms>``                         |
| iforms         | import | ``from django import forms``                                      |
| ipostgresff    | import | ``from django.contrib.postgres.forms import <PostgresSQL_forms>`` |
| clean_data     | method | ``validate form data``                                            |

### Snippets for Django Models

|    Abbreviation    |  Type  |                         Code - Description                          |
| ------------------ | ------ | ------------------------------------------------------------------- |
| Model              | class  | ``Simple Model Class``                                              |
| Model_full         | class  | ``Full Model Class(with TODOs)``                                    |
| modelmixin         | class  | ``Simple Model Class Mixin with Meta abstract = True``              |
| qs                 | class  | ``Custom QuerySet models.Queryset``                                 |
| mngr               | class  | ``Custom Manager models.Manager``                                   |
| qs_mngr            | class  | ``Custom initial QuerySet Manager returns``                         |
| mauto              | field  | ``models.AutoField()``                                              |
| mbigauto           | field  | ``models.BigAutoField()``                                           |
| mbigint            | field  | ``models.BigIntegerField()``                                        |
| mbinary            | field  | ``models.BinaryField()``                                            |
| mbool              | field  | ``models.BooleanField()``                                           |
| mchar              | field  | ``models.CharField()``                                              |
| mcoseint           | field  | ``models.CommaSeparatedIntegerField() - deprecated since 1.9``      |
| mdate              | field  | ``models.DateField()``                                              |
| mdatetime          | field  | ``models.DateTimeField()``                                          |
| mdecimal           | field  | ``models.DecimalField()``                                           |
| mduration          | field  | ``models.DurationField()``                                          |
| memail             | field  | ``models.EmailField()``                                             |
| mfile              | field  | ``models.FileField()``                                              |
| mfilepath          | field  | ``models.FilePathField()``                                          |
| mfloat             | field  | ``models.FloatField()``                                             |
| mimg               | field  | ``models.ImageField()``                                             |
| mint               | field  | ``models.IntegerField()``                                           |
| mgenericip         | field  | ``models.GenericIPAddressField()``                                  |
| mip                | field  | ``models.IPAddressField() - deprecated since version 1.7``          |
| mnullbool          | field  | ``models.NullBooleanField()``                                       |
| mphone             | field  | ``models.PhoneNumberField()``                                       |
| mposint            | field  | ``models.PositiveIntegerField()``                                   |
| mpossmallint       | field  | ``models.PositiveSmallIntegerField()``                              |
| mslug              | field  | ``models.SlugField()``                                              |
| msmallint          | field  | ``models.SmallIntegerFiled()``                                      |
| mtext              | field  | ``models.TextField()``                                              |
| mtime              | field  | ``models.TimeField()``                                              |
| murl               | field  | ``models.URLField()``                                               |
| musstate           | field  | ``models.USStateField()``                                           |
| muuid              | field  | ``models.UUIDField()``                                              |
| mxml               | field  | ``models.XMLField() - deprecated since version 1.3``                |
| fk                 | field  | ``models.ForeignKey()``                                             |
| m2m                | field  | ``models.ManyToManyField()``                                        |
| o2o                | field  | ``models.OneToOneField()``                                          |
| mstore             | field  | ``HStoreField() - PostgreSQL specific model field``                 |
| mjson              | field  | ``JSONField()- PostgreSQL specific model field``                    |
| marray             | field  | ``ArrayField()- PostgreSQL specific model field``                   |
| fmai               | import | ``from .managers import <local_managers>``                          |
| fmi                | import | ``from .models import <local_models>``                              |
| imodels            | import | ``from django.db import models``                                    |
| iuc                | import | ``from django.utils.encoding import python_2_unicode_compatible``   |
| ipostgresmf        | import | ``from django.contrib.postgres.fields import <PostgresSQL_models>`` |
| isignals           | import | ``from django.db.models.signals import <signals>``                  |
| str                | method | ``Unicode default python3``                                         |
| get\_absolute\_url | method | ``Calculate the canonical URL for an object``                       |
| receiver           | method | ``connect a receiver to a signal``                                  |


### Snippets for Django Views

|    Abbreviation    |  Type  |                        Code                         |
| ------------------ | ------ | --------------------------------------------------- |
| createview         | class  | ``Generic Create View``                             |
| updateview         | class  | ``Generic Update View``                             |
| deleteview         | class  | ``Generic Delete View``                             |
| detailview         | class  | ``Generic Detail View``                             |
| listview           | class  | ``Generic List View``                               |
| templateview       | class  | ``Generic Template View``                           |
| fvi                | import | ``from .views import <local_views>``                |
| igenericviews      | import | ``from django.views.generic import <genericViews>`` |
| isettings          | import | ``from django.conf import settings``                |
| dispatch           | method | ``dispatch method for CBVs``                        |
| get\_context\_data | method | ``get_context_data method for CBVs``                |
| view               | method | ``Function Based View``                             |
| get_queryset       | method | ``get_queryset method for CBVs``                    |


### Snippets for Python

| Abbreviation |  Type  |                Code - Description                 |
| ------------ | ------ | ------------------------------------------------- |
| \_\_init\_\_     | method | ``__init__(self, *args, **kwargs)``               |
| pdb          | method | ``import pdb ; pdb.set_trace()``                  |
| ipdb         | method | ``import ipdb ; ipdb.set_trace()``                |
| npdb         | method | ``from nose.tools import set_trace; set_trace()`` |
| traceback    | method | ``import traceback; traceback.print_exc();``      |
| utfc         | method | ``coding: utf-8 ``                                |
| iul          | import | ``from __future__ import unicode_literals``       |

### Snippets for Django templates

| Abbreviation   | Tag                                                   |
|----------------|-------------------------------------------------------|
| autoescape     | ``{% autoescape %} {% autoescape %}``                 |
| block          | ``{% block %} {% endblock %}``                        |
| comment        | ``{% comment %} {% endcomment %}``                    |
| csrf           | ``{% csrf_token %}``                                  |
| cycle          | ``{% cycle %}``                                       |
| debug          | ``{% debug %}``                                       |
| ext            | ``{% extends '' %}``                                  |
| extends        | ``{% extends '' %}``                                  |
| filter         | ``{% filter %} {% endfilter %}``                      |
| firstof        | ``{% firstof %}``                                     |
| for            | ``{% for in %} {% endfor %}``                         |
| fore           | ``{% for in %} {% empty %} {% endfor %}``             |
| if             | ``{% if %} {% endif %}``                              |
| ifchanged      | ``{% ifchanged %} {% endifchanged %}``                |
| ife            | ``{% if %} {% else %} {% endif %}``                   |
| ifelse         | ``{% if %} {% else %} {% endif %}``                   |
| ifeq           | ``{% ifequal %} {% endifequal %}``                    |
| ifequal        | ``{% ifequal %} {% endifequal %}``                    |
| ifnotequal     | ``{% ifnotequal %} {% endifnotequal %}``              |
| inc            | ``{% include %}``                                     |
| include        | ``{% include %}``                                     |
| load           | ``{% load %}``                                        |
| now            | ``{% now '' %}``                                      |
| regroup        | ``{% regroup by as %}``                               |
| spaceless      | ``{% spaceless %} {% endspaceless %}``                |
| ssi            | ``{% ssi %}``                                         |
| static         | ``{% static %}``                                      |
| templatetag    | ``{% templatetag %}``                                 |
| url            | ``{% url %}``                                         |
| verbatim       | ``{% verbatim %} {% endverbatim %}``                  |
| widthratio     | ``{% widthratio %}``                                  |
| with           | ``{% with as %} {% endwith %}``                       |
| trans          | ``{% trans %}``                                       |
| blocktrans     | ``{% blocktrans with as %} {% endblocktrans %}``      |
| super          |  ``{{ block.super }}``                                |
| extrahead      |  ``{% block extrahead %} {% endblock extrahead %}``   |
| extrastyle     |  ``{% block extrastyle %} {% endblock extrastyle %}`` |
| var            |  ``{{ }}``                                            |
| tag            |  ``{% %}``                                            |
| staticu        |  ``{{ STATIC_URL }}``                                 |
| media          |  ``{{ MEDIA_URL }}``                                  |


### 1.4.2

Undo force django-html lang to allow both standard html and django tags to autocomplete. Use django-html language to use django specific grammer.

### 1.4.1

Define new django-html lang instead of overriding html. Thanks ajitid!

### 1.4.0

Update snippets for admin, forms, models, urls, views and python.
Added Django version number when field was deprecated to the snippet description.

see details: [CHANGELOG.md](https://github.com/klavman/vscode-djaneiro/blob/master/CHANGELOG.md)

### 1.3.0

Added moar python and django template support

### 1.2.0

Change docstrings to class definitions for flake8 compatibility
Updated model / form fields to utilize fields in Django 1.11
Clean up repo from initial sublime port

### 1.1.6

Fix admin inline spacing
Change from double quotes to single quotes in template tags
Updated logo

### 1.0.0

Initial port of Djaneiro for Visual Studio Code


##TODO: 

- 
