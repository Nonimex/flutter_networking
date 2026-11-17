# main.dart

```
import 'package:flutter/material.dart'; // default
import 'contact_list_screen.dart'; // use other class
void main() {
  runApp(MyApp());
}


class MyApp extends StatelessWidget{
  MyApp({super.key});

  @override
  Widget build(BuildContext context){
    return MaterialApp(
      title: 'Networking App',
      home: const MyContactList(),

    );
  }

}
```
