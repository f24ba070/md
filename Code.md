# Code
## ソースコード
```dart
import 'package:flutter/material.dart';

void main ()
{
    runApp(MyApp());
}

class MyApp extends StatelessWidget
{
    @override
    Widget build(BuildContext context) 
    {
        return MaterialApp
        (
            title: 'Flutter Demo',
            home: Text
        (
            'Hello,Fullutter World!!',
            style: TextStyle(fontDize:32.0),
        ),
        );
    }
}
```
***
## main
```dart
void main ()
{
    runApp( ウィジェット );
}
```

***
## 継承
```dart
class クラス名　extends StetalessWidget
{
    @override
    Widget build(BuildContext context)
    {
        return MaterialApp(...);
    }
}
```

***
## 引数
```dart
return MaterialApp
    (
        title: 'Flutter Demo',
        home: Text
    (
        'Hello,Fullutter World!!',
        style: TextStyle(fontDize:32.0),
    ),
    );
```