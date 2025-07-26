# p-0726

import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Text('안녕')
    );
  }
}
void main 이후 stless 치고 tap키 눌러서 만듦 그후 14줄 const 뒤에 MaterialApp치고 소괄호 안에 home:
안녕 이라고 텍스트 넣는경우
runAPP- 앱시작
