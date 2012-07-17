![Agiliq: Django Design Patterns](https://github.com/agiliq/django-design-patterns/raw/master/logo.png)

Django design patterns is a book about commonly occurring patterns in Django. Not
patterns in [GOF](http://c2.com/cgi/wiki?GangOfFour) sense, but patterns in the sense, we work this way, and it works
for us. For us it is a ~pattern of work~ sense.

The latest sources are always available from
http://github.com/agiliq/django-design-pattern
and latest html from http://agiliq.com/books/djangodesignpatterns/

To create a PDF version of the book on Ubuntu Linux:
  1. sudo apt-get install git texlive-full python-sphinx
  2. git clone https://github.com/agiliq/django-design-patterns.git
  3. cd django-design-patterns
  4. make latexpdf latex_paper_size=letter

The generated file is django-design-patterns/build/latex/djangodesignpatterns.pdf

To create ePUB verion of the book:
  1. git clone https://github.com/agiliq/django-design-patterns.git
  2. cd django-design-patterns
  3. make epub

The generated file is django-design-patterns/build/epub/DjangoDesignPatterns.epub

