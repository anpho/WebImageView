# WebImageView
==============

WebImageView for BlackBerry Cascades, a fork from https://github.com/RodgerLeblanc/WebImageView and improved with much better performance.

see code for details.




## how to use
register this control in your main.cpp:
```
qmlRegisterType<WebImageView>("lab.anpho", 1, 0, "WebImageView");
```

then you can use it in QML.

```
import lab.anpho 1.0
```

```
WebImageView{
	url : "http://someplace.com/somepic.jpg"
}
```

