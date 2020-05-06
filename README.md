<?xml version="1.0" encoding="utf-8" ?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android" android:versionCode="4" android:versionName="2.0.1" package="com.abc.mice" platformBuildVersionCode="8" platformBuildVersionName="2.2">
	<uses-permission android:name="android.permission.INTERNET" />
	<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
	<uses-sdk android:minSdkVersion="8" android:targetSdkVersion="8" />
	    <application android:allowBackup="true" android:icon="@drawable/tangkas" android:label="Revised" android:theme="@android:style/Theme.Black.NoTitleBar.Fullscreen">
		<activity android:label="@string/app_name" android:name="com.abc.mice.android.activity.GameActivity" android:screenOrientation="landscape" />
		<activity android:label="@string/app_name" android:name="com.abc.mice.android.activity.RoomActivity" android:screenOrientation="landscape" android:theme="@android:style/Theme.Dialog" />
		<activity android:label="@string/app_name" android:name="com.abc.mice.android.activity.PatcherActivity" android:screenOrientation="landscape">
			<intent-filter>
				<action android:name="android.intent.action.MAIN" />
				<category android:name="android.intent.category.LAUNCHER" />
			</intent-filter>
		</activity>
		<activity android:label="@string/app_name" android:name="com.abc.mice.android.activity.LoginActivity" android:screenOrientation="landscape" />
		<activity android:label="@string/app_name" android:name="com.abc.mice.android.activity.SettingsActivity" android:screenOrientation="landscape" android:theme="@android:style/Theme.Dialog" />
        <activity
            android:name="example.patch.PrefOverallActivity"
            android:label="Editor" >
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />
                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
        <activity android:name="example.patch.PrefDetailActivity" />
    </application>
</manifest>
 # cks4bu1
