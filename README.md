# Sample ConstraintLayout Flow

![](img/flow.png)



```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <androidx.constraintlayout.helper.widget.Flow
        android:id="@+id/containerFlow"
        android:layout_width="0dp"
        android:layout_height="200dp"
        app:constraint_referenced_ids="kotak_1,kotak_2,kotak_3,kotak_4,kotak_5,kotak_6"
        app:flow_verticalGap="8dp"
        app:flow_wrapMode="chain"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <View
        android:id="@+id/kotak_1"
        android:layout_width="120dp"
        android:layout_height="100dp"
        android:background="#B44141" />

    <View
        android:id="@+id/kotak_2"
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:background="#2974C9" />

    <View
        android:id="@+id/kotak_3"
        android:layout_width="140dp"
        android:layout_height="100dp"
        android:background="#2D971F" />

    <View
        android:id="@+id/kotak_4"
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:background="#451414" />

    <View
        android:id="@+id/kotak_5"
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:background="#092342" />

    <View
        android:id="@+id/kotak_6"
        android:layout_width="180dp"
        android:layout_height="100dp"
        android:background="#0B3806" />

</androidx.constraintlayout.widget.ConstraintLayout>
```