from __future__ import unicode_literals

from django.db import models

# Create your models here.

from django.utils import timezone

class Curso(models.Model):
 authorrr = models.ForeignKey('auth.user')
 title = models.CharField(max_length=100)
 text = models.TextField()
 create_date = models.DateTimeField(default= timezone.now)

def __str__(self):
 return self.title


