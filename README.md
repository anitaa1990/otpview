# otpview 
<img src="https://camo.githubusercontent.com/7a097bb07d47506d643804b222bb8ad2be336498/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4150492d392532422d6f72616e67652e7376673f7374796c653d666c6174" alt="API" data-canonical-src="https://img.shields.io/badge/API-9%2B-orange.svg?style=flat" style="max-width:100%;"> <a href="https://android-arsenal.com/details/1/4581"><img src="https://img.shields.io/badge/Android%20Arsenal-OtpView-blue.svg?style=flat" alt="Android Arsenal" data-canonical-src="https://img.shields.io/badge/Android%20Arsenal-OtpView-blue.svg?style=flat" style="max-width:100%;"></a>

A custom view class to enter a four digit code which is used often these days for authentication. 

<h2>How to integrate the library in your app?</h2>
<b>Gradle Dependecy</b></br>

```gradle
dependencies {
        compile 'com.an.otpview:otpview:0.1.0'
}
```

<b>Maven Dependecy</b></br>
```xml
<dependency>
  <groupId>com.an.otpview</groupId>
  <artifactId>otpview</artifactId>
  <version>0.1.0</version>
  <type>pom</type>
</dependency>
```

<h2>How to use the library</h2>

Add the below line to the root layout of your xml file:

```xml
xmlns:app="http://schemas.android.com/apk/res-auto"
```

```xml
.....
       <com.an.otpview
            android:id="@+id/otp_view"
            app:background_color="@android/color/black"
            android:inputType="number"
            app:otp_maxLength="1"
            app:otp_gravity="center"
            app:otp_textColor="@android:color/white"
            app:otp_textSize="@dimen/font_large"
            android:orientation="horizontal"
            android:layout_width="match_parent"
            android:layout_height="wrap_content" />
.....
```            


<h2>Attributes includes:</h2>

| Value         | Type |
| ------------- |:-------------:|
| inputType      | ```android:inputType``` |
| otp_maxLength      | ```app:otp_maxLength``` |
| otp_gravity      | ```app:otp_gravity``` |
| otp_textColor      | ```app:otp_textColor``` |
| otp_textSize      | ```app:otp_textSize``` |
| background_color      | ```app:background_color``` |
| background_color      | ```app:background_color``` |

That's pretty much it.
