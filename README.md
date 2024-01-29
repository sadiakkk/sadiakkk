<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/linearLayout"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:orientation="horizontal">


    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="51dp"
        android:background="#B10606"
        android:text="@string/GPA CALCULATOR"
        android:textColor="#B39DDB"
        android:textSize="30sp" />

    <TextView
        android:text="@string/web development"
        android:textSize="20sp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentStart="true"
        android:layout_marginTop="60dp"
        android:id="@+id/textView1" />

    <EditText
        android:id="@+id/editTextNumber2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="90dp"
        android:ems="10"
        android:hint="@android:string/autofill"
        android:inputType="number"
        android:minHeight="48dp"
        android:textColorHint="#546E7A"
        tools:ignore="DuplicateSpeakableTextCheck" />


    <TextView
        android:id="@+id/textView3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentStart="true"
        android:layout_marginStart="0dp"
        android:layout_marginTop="150dp"
        android:text="@string/ata mining"
        android:textSize="20sp" />

    <EditText
        android:id="@+id/editTextNumber4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="170dp"
        android:ems="10"
        android:hint="@android:string/autofill"
        android:inputType="number"
        android:minHeight="48dp" />
    <TextView
        android:id="@+id/textView5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentStart="true"
        android:layout_marginStart="0dp"
        android:layout_marginTop="210dp"
        android:text="@string/data base"
        android:textSize="20sp" />

    <EditText
        android:id="@+id/editTextNumber6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="230dp"
        android:ems="10"
        android:hint="@android:string/autofill"
        android:inputType="number"
        android:minHeight="48dp"
        tools:ignore="DuplicateIds" />
    <TextView
        android:id="@+id/textView10"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentStart="true"
        android:layout_marginStart="0dp"
        android:layout_marginTop="290dp"
        android:text="@string/software engineering"
        android:textSize="20sp" />

    <EditText
        android:id="@+id/editTextNumber7"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="310dp"
        android:ems="10"
        android:hint="@android:string/autofill"
        android:inputType="number"
        android:minHeight="48dp"
        tools:ignore="DuplicateIds" />
    <TextView
        android:id="@+id/textView8"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentStart="true"
        android:layout_marginStart="0dp"
        android:layout_marginTop="350dp"
        android:text="English"
        android:textSize="20sp" />

    <EditText
        android:id="@+id/editTextNumber9"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="390dp"
        android:ems="10"
        android:hint="@android:string/autofill"
        android:inputType="number"
        android:minHeight="48dp"
        tools:ignore="DuplicateIds" />

    <Button
        android:id="@+id/button"
        android:layout_width="242dp"
        android:layout_height="69dp"
        android:layout_marginTop="450dp"
        android:text="@string/your gpa is" />


</RelativeLayout>




