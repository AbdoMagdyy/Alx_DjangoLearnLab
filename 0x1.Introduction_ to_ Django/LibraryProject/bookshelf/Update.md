# Update the Book Title

```python
from bookshelf.models import Book

# Retrieve the book instance
book = Book.objects.get(title="1984")

# Update the book title
book.title = "Nineteen Eighty-Four"
book.save()

# Expected Output: Title updated successfully.
