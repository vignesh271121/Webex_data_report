pip install Django

django-admin startproject webex_report_gen

cd webex_report_gen

python manage.py startapp report_App

//report_downloads.py file

import requests

import datetime

import xlsxwriter

