BlurredImageView
=========
Tweak library to provide Blur ImageView

Use
--------------
* **Import the library**

* **Add to XML the app prefix**
```xml
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    ...
</LinearLayout>
```
* **Add Blur ImageView**
```xml
<mx.dragonflylabs.ui.BlurredImageView 
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:blurLevel="50" <!--Customizable 1 - 100 -->
    android:src="@drawable/ic_launcher"/>
```
