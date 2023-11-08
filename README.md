layout
![image](https://github.com/nqmgaming/image_with_close_button_layout/assets/94773751/aa4bdd50-ff78-493a-a2b5-6a6f4753b79e)


```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="wrap_content"
    android:layout_marginEnd="15dp"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_height="wrap_content">

    <ImageView
            android:id="@+id/view"
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:src="@drawable/ic_add_photo"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"/>

    <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:src="@drawable/close"
            app:layout_constraintEnd_toEndOf="@id/view"
            app:layout_constraintTop_toTopOf="parent"/>


</androidx.constraintlayout.widget.ConstraintLayout>
```
