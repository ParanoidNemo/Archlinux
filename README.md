Install BE::Shell or upgrade to the latest commit. Themes are made with QSS - Qt Style Sheets, while the menu files for the globalmenu applet follow a simple xml syntax.

# **Installation** #
## **Theme & Config** ##

### **By script** ###
Visit this [repo](https://github.com/Hombremaledicto/be.shell) and follow the istructions using the script created by HombreMaledicto

### **Manually** ###
Copy the Themes directory:

```
#!bash

cp -r Themes `kde4-config --localprefix`/share/apps/be.shell/
```

Copy the included be.shell file:

```
#!bash

cp be.shell `kde4-config --localprefix`/share/config/be.shell
```

Reload be.shell:

```
#!bash

kquitapp be.shell; sleep 2; be.shell
```


## **Scripts & Menu** ##
Copy the folders Menu, Scripts and the MainMenu.xml file:

```
#!bash

cp -R Menu Scripts MainMenu.xml `kde4-config --localprefix`/share/apps/be.shell
```

Make the scripts executable:

```
#!bash

chmod -R 777 `kde4-config --localprefix`/share/apps/be.shell/Scripts/*
```

Modify the username & password in Scripts/applet mail section to use the mail specific applet.



## **Flare Theme** ##

![flare1.png](https://bitbucket.org/repo/EynnxG/images/3890305617-flare1.png)

## **Eve Theme** ##

![Eve5.jpeg](https://bitbucket.org/repo/EynnxG/images/1532914547-Eve5.jpeg)

## **Code Theme** ##

![Code2.jpeg](https://bitbucket.org/repo/EynnxG/images/486403133-Code2.jpeg)

## **Void** ##

![Void.png](http://s30.postimg.org/7zpp2acgx/Void4.png)
