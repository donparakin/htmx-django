# htmx-django

Extensions for using [HTMX](https://htmx.org/)
(or [Unpoly](https://unpoly.com/)
or [Ajaxial](https://ajaxial.unmodernweb.com/)
or [htmz](https://leanrada.com/htmz/))
with [Django](https://www.djangoproject.com/).

By abstracting HTMX (and friends) just a wee bit more than packages like 
[django-htmx](https://django-htmx.readthedocs.io/en/latest/),
htmx-django does not need additional packages like
[django-template-partials](https://github.com/carltongibson/django-template-partials)
to provide a complete HTMX &amp; Django workflow.

If you have a small brain like me,
you might enjoy the simplicity of htmx-django.
Bigger brained developers might not like it, especially the tiny bits of magic,
and so might prefer the other packages.
That's fine: the others are great packages by great contributors.

### Coming (Very) Soon

### FAQ

* **Why htmx-django?**
  * I was finding that my Django views had lots of boilerplate code
  testing `request.htmx` (see docs for details).
  I tested it to decide which Django template to use for the response.
  So I thought, in the famous words of Raymond Hettinger,
  "[there must be a better way](https://www.google.com/search?q=raymond+hettinger+there+must+be+a+better+way)". 

* **Why not django-htmx?**
  * I tried it. (more answer soon) 

* **Why not django-htmx and django-template-partials?**
  * I tried this too. (more answer soon)

* **Why not just contribute to django-htmx?**
  * I tried. See [issue](https://github.com/adamchainz/django-htmx/issues/445).
    We had a different vision, I guess. 
