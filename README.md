import 'package:flutter/material.dart';
void main() => runApp(MyApp());
class MyApp extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return MaterialApp(
 home: RaisedButtonDemo(),
 );
 }
}
class RaisedButtonDemo extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return Scaffold(
 appBar: AppBar(title: Text('RaisedButton Example')),
 body: Center(
 child: RaisedButton(
 color: Colors.green, // Button background color
 textColor: Colors.white, // Text color
 onPressed: () {
 print('RaisedButton Pressed!');
 },
 child: Text('Click Me'),
 ),
 ),
 );
 }
}
