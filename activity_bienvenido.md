<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".inicio">
    <LinearLayout
        android:id="@+id/header"
        android:layout_width="match_parent"
        android:layout_height="118dp"
        android:layout_alignParentTop="true"
        android:layout_alignParentEnd="true"
        android:layout_marginEnd="0dp"
        android:background="#f8fcf8"
        android:gravity="center_vertical"
        android:orientation="horizontal"
        android:padding="16dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.518"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0">

        <!-- Primer ImageButton -->

        <!-- Segundo ImageButton -->

        <ImageButton
            android:id="@+id/icon_two"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="@android:color/transparent"
            android:src="@android:drawable/ic_menu_sort_by_size" />

        <TextView
            android:id="@+id/title"
            android:layout_width="228dp"
            android:layout_height="28dp"
            android:layout_weight="1"
            android:gravity="center"
            android:paddingStart="48dp"
            android:paddingEnd="48dp"
            android:text="@string/app_name"
            android:textColor="@color/black"
            android:textSize="20sp"
            android:textStyle="bold" />

        <ImageView
            android:id="@+id/imageView14"
            android:layout_width="59dp"
            android:layout_height="43dp"
            android:src="@drawable/logo"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.933"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.042" />

        <ImageButton
            android:id="@+id/icon_one"
            android:layout_width="70dp"
            android:layout_height="104dp"
            android:background="@android:color/transparent"
            android:src="@drawable/persona"
            android:scaleType="fitCenter"/>


    </LinearLayout>

    <RelativeLayout
        android:layout_width="407dp"
        android:layout_height="309dp"
        android:layout_below="@id/header"
        android:layout_alignParentStart="true"
        android:layout_alignParentEnd="true"
        android:layout_alignParentBottom="true"
        android:layout_marginStart="0dp"
        android:layout_marginEnd="4dp"
        android:layout_marginBottom="296dp"
        android:background="#f8fcf8"
        android:padding="16dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.298">

        <ImageView
            android:id="@+id/imageView7"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:layout_alignParentStart="true"
            android:layout_alignParentTop="true"
            android:layout_alignParentEnd="true"
            android:layout_alignParentBottom="true"
            android:padding="16dp"
            android:scaleType="centerCrop"
            android:src="@drawable/logobien"
            android:alpha="0.5" /> <!-- Reducción de opacidad al 50% -->


        <TextView
            android:id="@+id/welcome_title"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignTop="@+id/imageView7"
            android:layout_alignBottom="@+id/imageView7"
            android:layout_centerHorizontal="true"
            android:layout_marginTop="29dp"
            android:layout_marginBottom="216dp"
            android:text="@string/welcome_title"
            android:textColor="@color/white"
            android:textSize="24sp"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/welcome_subtitle"
            android:layout_width="wrap_content"
            android:layout_height="146dp"
            android:layout_alignParentStart="true"
            android:layout_alignParentTop="true"
            android:layout_alignParentEnd="true"
            android:layout_alignParentBottom="true"
            android:layout_marginStart="68dp"
            android:layout_marginTop="94dp"
            android:layout_marginEnd="66dp"
            android:layout_marginBottom="98dp"
            android:gravity="start|center_vertical"
            android:includeFontPadding="false"
            android:justificationMode="inter_word"
            android:lineSpacingExtra="4dp"
            android:padding="20dp"
            android:text="@string/welcome_subtitle"
            android:textColor="@color/white"
            android:textSize="20sp" />

    </RelativeLayout>

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentStart="true"
        android:layout_alignParentTop="true"
        android:layout_alignParentEnd="true"
        android:layout_alignParentBottom="true"
        android:layout_marginStart="6dp"
        android:layout_marginTop="361dp"
        android:layout_marginEnd="0dp"
        android:layout_marginBottom="1dp"
        android:background="#f8fcf8"
        android:orientation="vertical"
        android:padding="16dp">

        <LinearLayout
            android:layout_width="378dp"
            android:layout_height="330dp"
            android:layout_marginTop="16dp"
            android:background="@drawable/fondo"
            android:orientation="vertical"
            android:padding="16dp">

            <ImageView
                android:layout_width="64dp"
                android:layout_height="64dp"
                android:layout_gravity="center_vertical"
                android:background="@color/black"
                android:scaleType="centerCrop" />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp"
                android:orientation="vertical">

                <TextView
                    android:id="@+id/item_name_label"
                    android:layout_width="128dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="Nombre del producto:"
                    android:textColor="#4e9750"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/item_name"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="(Nombre del producto)"
                    android:textColor="@color/black"
                    android:textSize="16sp" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp"
                android:orientation="horizontal">

                <TextView
                    android:id="@+id/dos"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="Tipo:"
                    android:textColor="#4e9750"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/trescu"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="(Tipo)"
                    android:textColor="@color/black"
                    android:textSize="16sp" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp"
                android:orientation="horizontal">

                <TextView
                    android:id="@+id/item_quantity_label"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="Cantidad:"
                    android:textColor="#4e9750"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/item_quantity"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="(Cantidad)"
                    android:textColor="@color/black"
                    android:textSize="16sp" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp"
                android:orientation="horizontal">

                <TextView
                    android:id="@+id/item_feE_label"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="Fecha de entrada:"
                    android:textColor="#4e9750"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/item_feE"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="(Fecha de entrada)"
                    android:textColor="@color/black"
                    android:textSize="16sp" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp"
                android:orientation="horizontal">

                <TextView
                    android:id="@+id/item_feS_label"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="Fecha de salida:"
                    android:textColor="#4e9750"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/item_feS"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="(Fecha de salida)"
                    android:textColor="@color/black"
                    android:textSize="16sp" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal">

                <TextView
                    android:id="@+id/item_Pre_label"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="Precio:"
                    android:textColor="#4e9750"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/item_Pre"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="(Precio)"
                    android:textColor="@color/black"
                    android:textSize="16sp" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal">

                <TextView
                    android:id="@+id/item_codigo"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="Codigo:"
                    android:textColor="#4e9750"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/item_Pred"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="(Codigo)"
                    android:textColor="@color/black"
                    android:textSize="16sp" />
            </LinearLayout>

        </LinearLayout>

    </LinearLayout>


</RelativeLayout>
