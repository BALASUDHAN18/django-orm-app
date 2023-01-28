# Django ORM Web Application

AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

Entity Relationship Diagram
output
![bala1](https://user-images.githubusercontent.com/118807740/215250421-e02f1eb1-ab44-45fc-be6f-ee5557c128e9.png)

DESIGN STEPS
STEP 1:
Created table and inserted values to it in the django applications

STEP 2:
Implementation of python code in README.md file

STEP 3:
Uploading the necessary files

STEP 4:
Pushing it to the github account

PROGRAM
```
from django.db import models
from django.contrib import admin
# Create your models here.
class Carsinfo(models.Model):
    registrationno = models.CharField(max_length=10,primary_key=True)
    brandname = models.CharField(max_length=100)
    mileage = models.IntegerField()
    dateofmanufacture = models.DateField()
    modelname = models.CharField(max_length=100)

class CarsinfoAdmin(admin.ModelAdmin):
    list_display = ('registrationno','brandname','mileage','dateofmanufacture','modelname')
OUTPUT
Carsinfo
```
output
![bala2](https://user-images.githubusercontent.com/118807740/215250447-904c7da1-cb51-4190-b3cb-2402c0b8719a.png)
![bala3](https://user-images.githubusercontent.com/118807740/215250458-3bbd3ab2-129d-4e6b-8e6d-3057eb935c81.png)

RESULT
The program was executed successfully.
