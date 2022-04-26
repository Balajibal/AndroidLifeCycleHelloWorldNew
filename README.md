# AndroidLifeCycleHelloWorldNew
# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min. required Artic Fox)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as “ex.no.1″ and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
/*
Program to print the text “Hello World”.
Developed by: BALAJI N
Registeration Number : 212220230006
*/

## MainActivity.java:
package com.example.exno1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast=Toast.makeText(getApplicationContext(),"OnCreate Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Executed",Toast.LENGTH_LONG);
        toast.show();
    }
}
## activity_main.xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>

## OUTPUT
![WhatsApp Image 2022-04-18 at 8 57 25 AM](https://user-images.githubusercontent.com/75234946/163749981-92c2efda-642d-4c72-aa1b-777e50944a7f.jpeg)
![WhatsApp Image 2022-04-18 at 8 57 25 AM (1)](https://user-images.githubusercontent.com/75234946/163750006-dab755d2-55e7-4684-8350-bf1b789b8d70.jpeg)
![WhatsApp Image 2022-04-18 at 8 57 26 AM](https://user-images.githubusercontent.com/75234946/163750032-c26d2ed0-d53b-4559-91d6-0237d6ca24db.jpeg)
![WhatsApp Image 2022-04-18 at 8 57 26 AM (1)](https://user-images.githubusercontent.com/75234946/163750056-ab3ffebf-6142-4f4b-bbb1-469691631271.jpeg)
![WhatsApp Image 2022-04-18 at 8 57 27 AM](https://user-images.githubusercontent.com/75234946/163750193-2e642018-e0ab-4354-92bd-0a22ed75e5b9.jpeg)
![WhatsApp Image 2022-04-18 at 8 57 27 AM (1)](https://user-images.githubusercontent.com/75234946/163750240-970cdc6b-ca28-45cf-b37b-c94740a30bd7.jpeg)
![WhatsApp Image 2022-04-18 at 8 57 27 AM (2)](https://user-images.githubusercontent.com/75234946/163750279-31da2613-5b52-44b5-8066-104b315eaff3.jpeg)
![WhatsApp Image 2022-04-18 at 8 57 28 AM](https://user-images.githubusercontent.com/75234946/163750303-2bdc1610-6c1d-4bca-8c91-2e2fb0218dfd.jpeg)
![WhatsApp Image 2022-04-18 at 8 57 28 AM (1)](https://user-images.githubusercontent.com/75234946/163750351-a38d9546-7c58-44f8-8a5e-b7245fa515cd.jpeg)




## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
