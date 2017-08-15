# otpview
<img src="https://camo.githubusercontent.com/7a097bb07d47506d643804b222bb8ad2be336498/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4150492d392532422d6f72616e67652e7376673f7374796c653d666c6174" alt="API" data-canonical-src="https://img.shields.io/badge/API-9%2B-orange.svg?style=flat" style="max-width:100%;">

A custom view class to enter a four digit code which is used often these days for authentication. 
You can download the aar file from the release folder in this project.</br>

<h2>How to use the library</h2>

```xml
.....
       <com.airloyal.black.views.CustomOtpView
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

That's pretty much it.
