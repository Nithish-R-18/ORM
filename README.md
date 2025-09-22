# Ex02 Django ORM Web Application
# Date: 21.09.2025
# AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).


## DESIGN STEPS
## STEP 1:
Clone the problem from GitHub

## STEP 2:
Create a new app in Django project

## STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Execute Django admin and create details for 10 books

# PROGRAM
```
admin.py

from django.contrib import admin
from.models import car,carAdmin
admin.site.register(car,carAdmin)

models.py

from django.db import models
from django.contrib import admin
class car(models.Model):
    car = models.CharField(max_length=255)
    model = models.CharField(max_length=100)
    manufacture_date = models.DateField
    type = models.CharField(max_length=50)
    price = models.IntegerField

class carAdmin(admin.ModelAdmin):
    list_display = ('car','model','manufacture_date','type','price')

```
# OUTPUT

![alt text](<Screenshot 2025-09-21 225132.png>)

# RESULT
Thus the program for creating a database using ORM hass been executed successfully
