Multiple User Types | Django
==============================

Multiple User Types | Django


How to Implement multiple user types with Django in a maintainable way.

For more Exploring CookieCutter, https://djangopackages.org

Django Proxy Model docs: https://docs.djangoproject.com/en/3.0/topics/db/models/#proxy-models

# Sample data

From within the `shell_plus` environment:

``` python
Spy.objects.create(username='hasnain', email='hasnain@django.com')
Driver.objects.create(username='test', email='test@django.com')    
Driver.objects.create(username='test1', email='test1@django.com') 
```