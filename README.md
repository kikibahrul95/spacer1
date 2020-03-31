# spacer1
flutter
import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("latihanspacer"),
        ),
        body: Center(child: Row(
          ///mainAxisAlignment: MainAxisAlignment.spaceBetween,
          children: <Widget>[
            Spacer(flex: 1,),
            Container(width: 80,height: 80,color: Colors.redAccent,),
            Spacer(flex: 2,),
             Container(width: 80,height: 80,color: Colors.blueGrey,),
             Spacer(flex: 3,),
              Container(width: 80,height: 80,color: Colors.black45,),
              Spacer(flex: 1,)
          ],
        ),)
      ),
    );
  }
}
