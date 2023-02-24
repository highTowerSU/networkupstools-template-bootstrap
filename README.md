# networkupstools-template-bootstrap
Template for nut-cgi (https://networkupstools.org/) with bootstrap

## Install
Put assets folder and header html to

/usr/share/nut/www

put both upsstats*.html to /etc/nut

Add alias to the apache configuration in /etc/apache2/conf.d:

Alias /nut /usr/share/nut/www

## Preview
### upsstats.html
![grafik](https://user-images.githubusercontent.com/3651850/221295472-04270b04-13fd-415b-b6dc-6f3a4abdfe77.png)

### upsstats-single.html
![grafik](https://user-images.githubusercontent.com/3651850/221295517-48651c4e-fdeb-437d-94d7-c779542af9d2.png)
