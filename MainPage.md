<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent" android:layout_height="match_parent">

    <GridLayout
        android:layout_width="277dp"
        android:layout_height="fill_parent"
        android:layout_gravity="right"
        android:id="@+id/main"
        android:foregroundGravity="center">

        <GridLayout
            android:layout_width="match_parent"
            android:layout_height="82dp"
            android:layout_row="0"
            android:layout_column="1">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:textAppearance="?android:attr/textAppearanceLarge"
                android:text="Status"
                android:id="@+id/Status"
                android:layout_row="0"
                android:layout_column="0" />

            <EditText
                android:layout_width="161dp"
                android:layout_height="wrap_content"
                android:id="@+id/addStatus"
                android:layout_row="0"
                android:layout_column="2" />

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:textAppearance="?android:attr/textAppearanceLarge"
                android:text="Music"
                android:id="@+id/Music"
                android:layout_row="2"
                android:layout_column="0" />

            <EditText
                android:layout_width="163dp"
                android:layout_height="wrap_content"
                android:id="@+id/addMusic"
                android:layout_row="2"
                android:layout_column="2" />
        </GridLayout>

        <LinearLayout
            android:orientation="vertical"
            android:layout_width="match_parent"
            android:layout_height="211dp"
            android:layout_row="1"
            android:layout_column="1">

            <EditText
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:id="@+id/PostPerson"
                android:layout_gravity="center_horizontal"
                android:text="Post" />

            <EditText
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:id="@+id/Music"
                android:layout_gravity="center_horizontal"
                android:text="Music Post" />

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:textAppearance="?android:attr/textAppearanceLarge"
                android:text="comment"
                android:id="@+id/shComment"
                android:layout_gravity="center_horizontal" />

            <GridLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_gravity="center_horizontal"
                android:id="@+id/ctrComment">

                <Button
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Like"
                    android:id="@+id/LikeB"
                    android:layout_row="2"
                    android:layout_column="0" />

                <Button
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Comment"
                    android:id="@+id/CommentB"
                    android:layout_row="2"
                    android:layout_column="1" />

                <Button
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Share"
                    android:id="@+id/shareB"
                    android:layout_row="2"
                    android:layout_column="3" />
            </GridLayout>
        </LinearLayout>

        <LinearLayout
            android:orientation="vertical"
            android:layout_width="match_parent"
            android:layout_height="211dp"
            android:layout_row="4"
            android:layout_column="1" >

            <EditText
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:id="@+id/editText"
                android:layout_gravity="center_horizontal"
                android:text="Post" />

            <EditText
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:id="@+id/editText2"
                android:layout_gravity="center_horizontal"
                android:text="Music Post" />

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:textAppearance="?android:attr/textAppearanceLarge"
                android:text="comment"
                android:id="@+id/textView2"
                android:layout_gravity="center_horizontal" />

            <GridLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_gravity="center_horizontal"
                android:id="@+id/gridLayout" >

                <Button
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Like"
                    android:id="@+id/button4"
                    android:layout_row="2"
                    android:layout_column="0" />

                <Button
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Comment"
                    android:id="@+id/button5"
                    android:layout_row="2"
                    android:layout_column="1" />

                <Button
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Share"
                    android:id="@+id/button6"
                    android:layout_row="2"
                    android:layout_column="3" />
            </GridLayout>
        </LinearLayout>

        <ScrollView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:id="@+id/scrollMainP"
            android:layout_row="0"
            android:layout_rowSpan="5"
            android:fillViewport="false" />
    </GridLayout>

    <GridLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_gravity="right"
        android:id="@+id/controlPanel">

        <Button
            android:layout_width="match_parent"
            android:layout_height="91dp"
            android:text="Home"
            android:id="@+id/homeB"
            android:layout_row="0"
            android:layout_column="0" />

        <Button
            android:layout_width="match_parent"
            android:layout_height="93dp"
            android:text="Status"
            android:id="@+id/statusB"
            android:layout_row="1"
            android:layout_column="0" />

        <Button
            android:layout_width="117dp"
            android:layout_height="93dp"
            android:text="Follow"
            android:id="@+id/followB"
            android:layout_row="2"
            android:layout_column="0" />
    </GridLayout>
</LinearLayout>
