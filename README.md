# Django CV Builder

You can use this custom Django application to build resume and eventually print as a PDF or share as a link with anyone.

Application Main Menu
------

[![](https://s3.ozan.pl/static/github-images/cvbuilder-mainpage.png)](https://s3.ozan.pl/static/github-images/cvbuilder-mainpage.png)

Final Generated Resume Sample
------

[![](https://s3.ozan.pl/static/github-images/cvbuilder-sample.png)](https://s3.ozan.pl/static/github-images/cvbuilder-sample.png)


Installation
------

1. Install all required packages from requirements.txt

```
pip install -r requirements.txt
```

2. Complete all of the migrations

```
python manage.py makemigrations
python manage.py migrate
```

3. Create a super user for yourself

```
python manage.py createsuperuser
```

4. If you want to use a template color other than blue, Go to Admin page > Templates > Add the the name of below templates, which you want to use color of:

- "Default Blue"
- "Default Green"
- "Default Maroon"
- "Default Steelblue"
- "Default Violet"

Note: To be able to use the print function from the server, you need to initially install wkhtml2pdf in your machine.
In linux, you can use the following command to be able to install:

```
sudo apt-get install -y wkhtmltopdf xvfb
```

Otherwise, you can always print the CV using Google Chrome's built-in "Print to PDF" functionality.

If you liked the application, you can always show your appreciation by starring my repo :) 

In case you have any trouble, you can reach me out directly using the below link:

https://www.ozan.pl/contact/

Cheers,
Ozan Tellioglu