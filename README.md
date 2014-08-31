Palette Pack
===
This repository is contaning color palette collections from some source. For documentation in English please see [README][0]

---

Repositori ini berisi koleksi palet warna yang didasarkan dari beberapa sumber. Disediakan dua jenis format palet warna. Pertama, berkas berekstensi .xml adalah [Android color resources][4] yang berisi kumpulan warna dalam format Heksadesimal. Kedua berkas berekstensi .gpl adalah palette yang bisa digunakan untuk aplikasi GIMP dan Inkscape.

Pemasangan
---
**Proyek Android**
Untuk menggunakan kumpulan warna pada berkas **colors.xml** anda cukup menyalinnya ke direktori
>NamaProyekAndroid/res/values/

Contoh pemakaian warna pada layout Android
```xml
<TextView
    android:layout_width="fill_parent"
    android:layout_height="wrap_content"
    android:textColor="@color/clouds"
    android:background="@color/pomegranate"
    android:text="Hello"/>
```
Contoh pemakaian pada kode Android
```java
txName.setBackgroundColor(getResources().getColor(R.color.pomegranate));
txName.setTextColor(getResources().getColor(R.color.clouds));
```

Pratampil
---
***Bootflat***

![Bootflat](https://raw.githubusercontent.com/asrarlabs/palette-pack/master/bootflat/preview.png)

***Flat UI***

![Flat UI](https://raw.githubusercontent.com/asrarlabs/palette-pack/master/flat-ui/preview.png)

***Flat UI Color Picker***

![Flat UI Color Picker](https://raw.githubusercontent.com/asrarlabs/palette-pack/master/flat-ui-color-picker/preview.png)

Sumber
---
* [Bootflat] [1]
* [Flat UI][2]
* [Flat UI Color Picker][3]

[0]:https://github.com/asrarlabs/palette-pack/blob/master/README.en.md
[1]:http://bootflat.github.io/documentation.html
[2]:http://designmodo.github.io/Flat-UI/
[3]:http://www.flatuicolorpicker.com/
[4]:http://developer.android.com/guide/topics/resources/more-resources.html#Color