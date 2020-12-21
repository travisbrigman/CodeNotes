# CodeNotes

### Python/Django Command Cheat Sheet

`python manage.py migrate` - Run this on installation of Django ReST framework and any time after running `python manage.py makemigrations {projectName}`

`python manage.py makemigrations {projectName}` - run after creating Class Models that will be used to generate database tables

`python manage.py loaddata {fixtureName}` seeds your database with JSON files that are in fixtures directory

`python manage.py runserver` - starts the Django app (server)

`var jsonDate = (new Date()).toJSON();` - creates a date in ISO extended format (YYYY-MM-DDT00:00)

  the .map extracts the make property from items array. The filter returns only distinct make values
  `const makeList = itemsCopy.map(item => item.make).filter((value, index, self) => self.indexOf(value) === index)`
