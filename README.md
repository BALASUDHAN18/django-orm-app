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
![bala2](https://user-images.githubusercontent.com/118807740/215270001-5edcb912-dcde-43ce-b92b-0e8d4b93c5f1.png)

![bala3](https://user-images.githubusercontent.com/118807740/215270232-ffcd3bd2-70c2-4bdd-a400-6d98330ddc8d.png)

RESULT
The program was executed successfully.
