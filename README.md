# customeButtonText

import 'package:flutter/material.dart';

class CustomButtonText extends StatelessWidget {
  final String text;
  final Color color;

  const CustomButtonText({
    Key? key,
    required this.text,
    this.color = Colors.white, // Default color is white
  }) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Text(
      text,
      style: TextStyle(
        color: color,
        fontSize: 18, // Default font size
        fontWeight: FontWeight.bold, // Optional styling
      ),
    );
  }
}
