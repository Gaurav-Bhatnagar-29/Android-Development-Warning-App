<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="20dp">

    <ImageView
        android:id="@+id/gaurav"
        android:layout_width="120dp"
        android:layout_height="120dp"
        android:layout_gravity="center"
        android:src="@drawable/gaurav"
        android:contentDescription="" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Student Name"
        android:layout_gravity="center"
        android:textSize="18sp"
        android:textStyle="bold"
        android:layout_marginTop="10dp" />

    <EditText
        android:id="@+id/et1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:inputType="text"
        android:hint="Enter Name" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Registration Number"
        android:layout_gravity="center"
        android:textStyle="bold"
        android:textSize="18sp" />

    <EditText
        android:id="@+id/et2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Enter Registration Number"
        android:inputType="text"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Total Classes Conducted"
        android:textStyle="bold"
        android:layout_gravity="right"
        android:layout_marginTop="10dp"
        android:textSize="18sp" />

    <EditText
        android:id="@+id/et3"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Enter Total Classes"
        android:inputType="number" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Classes Attended"
        android:layout_gravity="right"
        android:textStyle="bold"
        android:layout_marginTop="10dp"
        android:textSize="18sp" />

    <EditText
        android:id="@+id/et4"
        android:hint="Enter Classes Attended"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:inputType="number" />

    <Button
        android:id="@+id/btn"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Check Eligibility"
        android:layout_marginTop="20dp" />


</LinearLayout>
