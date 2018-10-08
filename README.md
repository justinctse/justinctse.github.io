Justin Tse's Portfolio
=========================
I removed the following code to remove the contact me in default.html, if wanted put it after include about.html
```
    <!--{% if site.contact == "static" %}-->
    <!--{% include contact_static.html %}-->
    <!--{% elsif site.contact == "disqus" %}-->
    <!--{% include contact_disqus.html %}-->
    <!--{% else %}-->
    <!--{% include contact.html %}-->
    <!--{% endif %}-->
```
___
### Credits
This portfolio is based on the [Freelancer Jekyll theme](http://startbootstrap.com/template-overviews/freelancer/).
