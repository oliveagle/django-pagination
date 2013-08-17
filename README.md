django-pagination
=================

add 'PAGINATION_TEMPLATE' into settings.py 


2 ways to customize pagination appearance:
  1. modify css.
  2. modify template. ( add support of this way)

###howto modify pagination template

1. copy `django-pagination/templates/pagination/pagination.html` into your app templates directory. 
2. modify pagiantion.html according your needs.
3. add `PAGINATION_TEMPLATE` to your `settings.py`

  PAGINATION_TEMPLATE = "pagination.html"


