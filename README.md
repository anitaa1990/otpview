# otpview

A custom view class to enter a four digit code which is used often these days for authentication.


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
