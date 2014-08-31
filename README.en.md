Palette Pack
===

Instalation
---
**Android Project**
To use **colors.xml** just copy file to folder
>AndroidProjectFolder/res/values/

Example usage in Android Layout
```xml
<TextView
    android:layout_width="fill_parent"
    android:layout_height="wrap_content"
    android:textColor="@color/clouds"
    android:background="@color/pomegranate"
    android:text="Hello"/>
```
Example usage in Android code
```java
txName.setBackgroundColor(getResources().getColor(R.color.pomegranate));
txName.setTextColor(getResources().getColor(R.color.clouds));
```

Preview
---
***Bootflat***
![Alt text](https://raw.githubusercontent.com/asrarlabs/palette-pack/master/bootflat/preview.png)

***Flat UI***
![Alt text](https://raw.githubusercontent.com/asrarlabs/palette-pack/master/flat-ui/preview.png)

***Flat UI Color Picker***
![Alt text](https://raw.githubusercontent.com/asrarlabs/palette-pack/master/flat-ui-color-picker/preview.png)

Reference
---
* [Bootflat] [1]
* [Flat UI][2]
* [Flat UI Color Picker][3]

[0]:https://github.com/asrarlabs/palette-pack/blob/master/README.en.md
[1]:http://bootflat.github.io/documentation.html
[2]:http://designmodo.github.io/Flat-UI/
[3]:http://www.flatuicolorpicker.com/
[4]:http://developer.android.com/guide/topics/resources/more-resources.html#Color