# easy_switch

## About

Easy Switch - an easy switch widget for Flutter. Simple and good looking. 



## How to use

```dart
class HomeScreen extends StatefulWidget {
  @override
  _HomeScreenState createState() => _HomeScreenState();
}

class _HomeScreenState extends State<HomeScreen> {

  bool status = false;

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text('Easy Switch Example'),
      ),
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            EasySwitch(
              activeColor: Colors.pink,
              inactiveColor: Colors.grey
              value: status,
              onChanged: (value) {},
            ),
          ],
        ),
      ),
    );
  }
}
```

