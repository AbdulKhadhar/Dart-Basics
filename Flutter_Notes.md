# Flutter Notes

WHAT IS FLUTTER ?

Flutter is an open-source UI software development kit created by Google. It is used to develop cross platform applications for Android, iOS, Linux, macOS, Windows, Google Fuchsia, and the web from a single codebase
Flutter is not a programming language. It’s a software development kit (SDK) with prewritten code, consisting of ready-to-use and customizable widgets, as well as libraries, tools, and documentation that together serve to build cross-platform apps. Flutter’s language for cross-platform development is Dart, which was also developed by Google.

### STATEFUL WIDGET

The State is the information that can be read synchronously when the widget is built and might change during the lifetime of the widget.In other words, the state of the widget is the data of the objects that its properties are sustaining at the time of its creation . The state can also change when it is used for example when a CheckBox widget is clicked a check appears on the box.
##### syntax

 void main();
 class MyApp extends StatefulWidget {
 @override
 _MyAppState createState() => _MyAppState();
}
class _MyAppState extends State<MyApp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
  body:null,
     );
   }
  }
  
### STATELESS WIDGET

The widgets whose state can not be altered once they are built are called stateless widgets.These widgets are immutable once they are built i.e any amount of change in the variables, icons, buttons, or retrieving data can not change the state of the app.
##### syntax
 
 void main() ;
 
class MyApp extends StatefulWidget {
@override
Widget build(BuildContext context) {
    return Container();
     }
}
