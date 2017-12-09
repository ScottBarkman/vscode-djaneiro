# Django snippets for Visual Studio Code
A collection of snippets for django templates, models, views, fields & forms. Quit typing so much, will ya?

Initially ported to vscode from [Djaneiro for Sublime Text 2/3](https://github.com/squ1b3r/Djaneiro)

If you'd like to contribute to this collection of snippets, feel free to [submit a pull request on github](https://github.com/ScottBarkman/vscode-djaneiro)

## Features

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

### Snippets for Django model fields

| Abbreviation | Tag                                     |
|--------------|-----------------------------------------|
| mauto        | ``models.AutoField()``                  |
| mbigauto     | ``models.BigAutoField()``               |
| mbigint      | ``models.BigIntegerField()``            |
| mbinary      | ``models.BinaryField()``                |
| mbool        | ``models.BooleanField()``               |
| mchar        | ``models.CharField()``                  |
| mcoseint     | ``models.CommaSeparatedIntegerField()`` |
| mdate        | ``models.DateField()``                  |
| mdatetime    | ``models.DateTimeField()``              |
| mdecimal     | ``models.DecimalField()``               |
| mduration    | ``models.DurationField()``              |
| memail       | ``models.EmailField()``                 |
| mfile        | ``models.FileField()``                  |
| mfilepath    | ``models.FilePathField()``              |
| mfloat       | ``models.FloatField()``                 |
| mimg         | ``models.ImageField()``                 |
| mint         | ``models.IntegerField()``               |
| mgenericip   | ``models.GenericIPAddressField()``      |
| mip          | ``models.IPAddressField()``             |
| mnullbool    | ``models.NullBooleanField()``           |
| mphone       | ``models.PhoneNumberField()``           |
| mposint      | ``models.PositiveIntegerField()``       |
| mpossmallint | ``models.PositiveSmallIntegerField()``  |
| mslug        | ``models.SlugField()``                  |
| msmallint    | ``models.SmallIntegerFiled()``          |
| mtext        | ``models.TextField()``                  |
| mtime        | ``models.TimeField()``                  |
| murl         | ``models.URLField()``                   |
| musstate     | ``models.USStateField()``               |
| muuid        | ``models.UUIDField()``                  |
| mxml         | ``models.XMLField()``                   |
| fk           | ``models.ForeignKey()``                 |
| m2m          | ``models.ManyToManyField()``            |
| o2o          | ``models.OneToOneField()``              |

### Snippets for Django form fields

| Abbreviation   | Code                                 |
|----------------|--------------------------------------|
| fbool          | ``forms.BooleanField()``             |
| fchar          | ``forms.CharField()``                |
| fchoice        | ``forms.ChoiceField()``              |
| fcombo         | ``forms.ComboField()``               |
| fdate          | ``forms.DateField()``                |
| fdatetime      | ``forms.DateTime()``                 |
| fdecimal       | ``forms.DecimalField()``             |
| fduration      | ``forms.DurationField()``            |
| femail         | ``forms.EmailField()``               |
| ffile          | ``forms.FileField()``                |
| ffilepath      | ``forms.FilePathField()``            |
| ffloat         | ``forms.FloatField()``               |
| fimg           | ``forms.ImageField()``               |
| fint           | ``forms.IntegerField()``             |
| fip            | ``forms.IPAddressField()``           |
| fgenericip     | ``forms.GenericIPAddressField()``    |
| fmochoice      | ``forms.ModelChoiceField()``         |
| fmomuchoice    | ``forms.ModelMultipleChoiceField()`` |
| fmuchoice      | ``forms.MultipleChoiceField()``      |
| ftypedmuchoice | ``forms.TypedMultipleChoiceField()`` |
| fmuval         | ``forms.MultipleValueField()``       |
| fnullbool      | ``forms.NullBooleanField()``         |
| fregex         | ``forms.RegexField()``               |
| fslug          | ``forms.SlugField()``                |
| fsdatetime     | ``forms.SplitDateTime()``            |
| ftime          | ``forms.TimeField()``                |
| ftchoice       | ``forms.TypedChoiceField()``         |
| ftmuchoice     | ``forms.TypedMultipleChoiceField()`` |
| furl           | ``forms.URLField()``                 |
| fuuid          | ``forms.UUIDField()``                |

### Snippets for Django Views

| Abbreviation     | Code                                 |
|------------------|--------------------------------------|
| view             | ``Function Based View``              |
| createview       | ``Generic Create View``              |
| updateview       | ``Generic Update View``              |
| deleteview       | ``Generic Delete View``              |
| detailview       | ``Generic Detail View``              |
| listview         | ``Generic List View``                |
| templateview     | ``Generic Template View``            |
| adminview        | ``Generic Admin View``               |
| tabularinline    | ``Tabular Inline View``              |
| stackedinline    | ``Stacked Inline View``              |
| dispatch         | ``dispatch method for CBVs``         |
| get_context_data | ``get_context_data method for CBVs`` |

### Snippets for Django Models

| Abbreviation     | Code                                 |
|------------------|--------------------------------------|
| Model            | ``Simple Model Class``               |
| Model_full       | ``Full Model Class(with TODOs)``     |

### Snippets for Python

| Abbreviation | Code                                              |
|--------------|---------------------------------------------------|
| __init__     | ``__init__(self, *args, **kwargs)``               |
| pdb          | ``import pdb ; pdb.set_trace()``                  |
| ipdb         | ``import ipdb ; ipdb.set_trace()``                |
| npdb         | ``from nose.tools import set_trace; set_trace()`` |
| traceback    | ``import traceback; traceback.print_exc();``      |
| utfc         | ``coding: utf-8 ``                                |

### Snippets for Django form import

| Abbreviation         | Code                                                      |
|----------------------|-----------------------------------------------------------|
| iadmin               | ``from django.contrib import admin``                      |
| ffi                  | ``from .forms import ``                                   |
| iforms               | ``from django import forms``                              |
| fmai                 | ``from .managers import``                                 |
| fmi                  | ``from .models import``                                   |
| imodels              | ``from django.db import models``                          |
| irmf                 | ``from redactor.fields import RedactorField``             |
| imjf                 | ``from django.contrib.postgres.fields import JSONField``  |
| isettings            | ``from django.conf import settings``                      |
| ilib                 | ``from django import template``                           |
| ireverse             | ``from django.core.urlresolvers import reverse`           |
| iurl                 | ``from django.conf.urls import url``                      |
| from views import    | ``from .views import``                                    |
| import createview    | ``from django.views.generic import CreateView``           |
| import detailview    | ``from django.views.generic import DetailView``           |
| import formview      | ``from django.views.generic import FormView``             |
| import listview      | ``from django.views.generic import ListView``             |
| import templateview  | ``from django.views.generic import TemplateView``         |
| import updateview    | ``from django.views.generic import UpdateView``           |




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

- Add Django version number when field was deprecated to the snippet description. Some of these field types are no longer used.
- Update view snippets
