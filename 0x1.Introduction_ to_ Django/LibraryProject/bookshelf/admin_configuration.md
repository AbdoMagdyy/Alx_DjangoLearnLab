# Admin Interface Configuration for Book Model

## Registering the Book Model

In `bookshelf/admin.py`, register the `Book` model with the following code:

```python
from django.contrib import admin
from .models import Book

admin.site.register(Book)
