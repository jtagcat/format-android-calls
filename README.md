# format-android-calls
golang decoder of vnd.android.cursor.dir/calls format

You can get a file with:
```
adb shell content query --uri content://call_log/calls
```

decodeToJson.go takes from either stdin or first CLI argument
