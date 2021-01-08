# flutter
/*import 'package:flutter/material.dart';

void main() => runApp(new MaterialApp(
      home: new myapp(),
    ));

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.menu),
          onPressed: () {
            print("click to enjoy");
          },
        ),
        title: Text('lakshmi narayanan'),
        actions: <Widget>[
          IconButton(
            icon: Icon(Icons.search),
            onPressed: () {},
          ),
          IconButton(
            icon: Icon(Icons.more_vert),
            onPressed: () {},
          ),
        ],
      ),
    );
  }
}*/

/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.menu),
          onPressed: () {
            print("i am grat app developer");
          },
        ),
        title: Text('lakshmi narayanan'),
        actions: <Widget>[
          IconButton(
            icon: Icon(Icons.search),
            onPressed: () {},
          ),
        ],
      ),
    );
  }
}*/

/*import 'dart:ffi';
import 'dart:ui';

import 'package:flutter/cupertino.dart';
import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.menu),
          onPressed: () {
            print('welocme to my app');
          },
        ),
        title: Text('devanand'),
        actions: <Widget>[
          IconButton(
            icon: Icon(Icons.search),
            onPressed: () {},
          ),
          IconButton(
            icon: Icon(Icons.more_vert),
            onPressed: () {},
          ),
        ],
        flexibleSpace: SafeArea(
          child: Icon(
            Icons.camera,
            color: Colors.white,
            size: 55.0,
          ),
        ),
        bottom: PreferredSize(
          child: Container(
            color: Colors.deepOrangeAccent,
            height: 75.0,
            width: double.infinity,
            child: Text(
              'lakshmi narayanan',
              style: TextStyle(color: Colors.amber, fontSize: 25.0),
            ),
          ),
          preferredSize: Size.fromHeight(75.0),
        ),
      ),
    );
  }
}*/
/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.menu),
          color: Colors.limeAccent,
          onPressed: () {
            print('lakshmi narayanan');
          },
        ),
        title: Text('devanand'),
        actions: <Widget>[
          IconButton(
            icon: Icon(Icons.access_alarm),
            color: Colors.yellowAccent,
            onPressed: () {},
          ),
          IconButton(
            icon: Icon(Icons.more_vert),
            onPressed: () {},
          ),
        ],
        flexibleSpace: SafeArea(
          child: IconButton(
            icon: Icon(Icons.account_circle_rounded),
            color: Colors.red,
            iconSize: 50.0,
          ),
        ),
      ),
    );
  }
}*/

/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.mail_outline),
          onPressed: () {
            print('press and enjoy');
          },
        ),
        title: Text('devanand'),
        actions: <Widget>[
          IconButton(
            icon: Icon(Icons.account_circle),
            onPressed: () {},
          ),
        ],
        flexibleSpace: SafeArea(
            child: IconButton(
          icon: Icon(Icons.ac_unit),
          color: Colors.limeAccent,
          iconSize: 50.0,
        )),
        bottom: PreferredSize(
          child: Container(
            color: Colors.deepOrange,
            height: 75.0,
            width: double.infinity,
            child: Text(
              "lakshmi narayanan",
              style: TextStyle(
                  backgroundColor: Colors.white,
                  color: Colors.deepOrange,
                  fontSize: 25.0),
            ),
          ),
          preferredSize: Size.fromHeight(75.0),
        ),
      ),
    );
  }
}*/
/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text(
          'lakshmi narayanana',
          style: TextStyle(color: Colors.tealAccent, fontSize: 10.0),
        ),
        flexibleSpace: SafeArea(
          child: Icon(
            Icons.camera,
            color: Colors.white,
            size: 50.0,
          ),
        ),
        bottom: PreferredSize(
          child: Container(
            color: Colors.yellowAccent,
            height: 56.0,
            width: double.infinity,
            child: Text(
              "lakshmi narayanan",
              style: TextStyle(
                  color: Colors.lime,
                  backgroundColor: Colors.tealAccent,
                  fontSize: 20.0),
            ),
          ),
          preferredSize: Size.fromHeight(75.0),
        ),
        actions: <Widget>[
          Icon(Icons.search),
        ],
      ),
      body: Center(
        child: Text(
          'lakshmi narayanana',
          style: TextStyle(fontSize: 28.0, color: Colors.deepOrange),
        ),
      ),
      floatingActionButton: FloatingActionButton(
        elevation: 10.0,
        child: Icon(Icons.add),
        onPressed: () {
          print('lakshmi narayanan');
        },
      ),
      floatingActionButtonLocation:
          FloatingActionButtonLocation. /*centerDocked*/ centerFloat,
      drawer: Drawer(
        elevation: 16.0,
        child: Column(
          children: <Widget>[
            UserAccountsDrawerHeader(
              accountName: Text('lakshmi narayanan'),
              accountEmail: Text('atechdev360@gmail.com'),
              currentAccountPicture: CircleAvatar(
                  backgroundColor: Colors.white, child: Text('abc')),
            ),
            ListTile(
              title: Text('All Inbox'),
              leading: Icon(Icons.mail),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(title: Text('All Primary'), leading: Icon(Icons.inbox)),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Social'),
              leading: Icon(Icons.people),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Promotions'),
              leading: Icon(Icons.local_offer),
            ),
            Divider(
              height: 0.1,
            ),
          ],
        ),
      ),
      persistentFooterButtons: <Widget>[
        RaisedButton(
          elevation: 10.0,
          onPressed: () {
            print('click');
          },
          color: Colors.deepOrange,
          child: Icon(Icons.add),
        ),
        RaisedButton(
          elevation: 10.0,
          onPressed: () {
            print('click');
          },
          color: Colors.green,
          child: Icon(Icons.clear),
        ),
      ],
    );
  }
}*/
/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.menu),
          onPressed: () {
            print('lakshmi narayanan');
          },
          color: Colors.orange,
        ),
        title: Text(
          'lakshmi narayanan',
          style: TextStyle(color: Colors.deepPurple, fontSize: 10.0),
        ),
        actions: <Widget>[
          IconButton(
            icon: Icon(Icons.ac_unit),
            onPressed: () {},
          ),
          Icon(Icons.mail)
        ],
        flexibleSpace: SafeArea(
          child: Icon(
            Icons.mail,
            color: Colors.green,
            size: 55.0,
          ),
        ),
        bottom: PreferredSize(
          child: Container(
            color: Colors.limeAccent,
            height: 75.0,
            width: double.infinity,
            child: Text('lakhmi narayanan'),
          ),
          preferredSize: Size.fromHeight(75.0),
        ),
      ),
    );
  }*/

/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}*/

/*class myapp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Text('lakshmi narayananan '),
    );
  }
}*/

/*class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  String value = 'yashwant';
  void clickme() {
    setState(() {
      value = 'lakshmi narayanan';
    });
  }

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Column(children: <Widget>[
          Text('$value'),
          FloatingActionButton(
            child: Icon(Icons.add),
            onPressed: clickme,
          )
        ],
      ),
    );
  }
}*/

/*class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  String value = 'devanand';
  void clickme() {
    setState(() {
      value = 'rajalakshmi';
    });
  }

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Column(
        children: <Widget>[
          Text('$value'),
          FloatingActionButton(child: Icon(Icons.add), onPressed: clickme)
        ],
      ),
    );
  }
}*/
/*class myapp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: SafeArea(child: Text('lakshmi narayanan')),
    );
  }
}*/
/*class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return new Scaffold(
      appBar: new AppBar(
        title: new Text('lakshmi narayanan'),
      ),
      body: new Container(child: new Text('i am new to flutter')),
    );
  }
}*/

/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}*/

/*class myapp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Text('lakshmi narayananan '),
    );
  }
}*/

/*class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  String value = 'yashwant';
  void clickme() {
    setState(() {
      value = 'lakshmi narayanan';
    });
  }

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Column(children: <Widget>[
          Text('$value'),
          FloatingActionButton(
            child: Icon(Icons.add),
            onPressed: clickme,
          )
        ],
      ),
    );
  }
}*/

/*class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  String value = 'devanand';
  void clickme() {
    setState(() {
      value = 'rajalakshmi';
    });
  }

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Column(
        children: <Widget>[
          Text('$value'),
          FloatingActionButton(child: Icon(Icons.add), onPressed: clickme)
        ],
      ),
    );
  }
}*/
/*class myapp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: SafeArea(child: Text('lakshmi narayanan')),
    );
  }
}*/
/*class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return new Scaffold(
      appBar: new AppBar(
        title: new Text('lakshmi narayanan'),
      ),
      body: new Container(child: new Text('i am new to flutter')),
    );
  }
}*/

/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.menu),
          onPressed: () {
            print("click me and enjoy");
          },
        ),
        leadingWidth: 56.0,
        backgroundColor: Colors.green,
        shadowColor: Colors.deepPurple,
        title: Text(
          'lakshmi narayanan',
          style: TextStyle(color: Colors.cyanAccent, fontSize: 10.0),
        ),
        actions: <Widget>[
          IconButton(icon: Icon(Icons.search), onPressed: () {}),
          IconButton(icon: Icon(Icons.more_vert), onPressed: () {}),
        ],
        flexibleSpace: SafeArea(
          child: Icon(
            Icons.camera,
            color: Colors.white,
            size: 50.0,
          ),
        ),
        bottom: PreferredSize(
          child: Container(
            color: Colors.yellowAccent,
            height: 56.0,
            width: double.infinity,
            child: Text(
              "lakshmi narayanan",
              style: TextStyle(
                  color: Colors.lime,
                  backgroundColor: Colors.tealAccent,
                  fontSize: 20.0),
            ),
          ),
          preferredSize: Size.fromHeight(75.0),
        ),
      ),
      body: Center(
        child: Text('lakshmi narayanan',
            style: TextStyle(color: Colors.orange, fontSize: 20.0)),
      ),
      floatingActionButton: FloatingActionButton(
        elevation: 10.0,
        child: Icon(Icons.add),
        onPressed: () {
          print('lakshmi narayanan');
        },
      ),
      floatingActionButtonLocation: FloatingActionButtonLocation.centerFloat,
      drawer: Drawer(
        elevation: 16.0,
        child: Column(
          children: <Widget>[
            UserAccountsDrawerHeader(
              accountName: Text('lakshmi narayanan'),
              accountEmail: Text('atechdev360@gmail.com'),
              currentAccountPicture: CircleAvatar(
                backgroundColor: Colors.tealAccent,
                child: Text('abc'),
              ),
            ),
            ListTile(
              title: Text('All Inbox'),
              leading: Icon(Icons.mail),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(title: Text('All Primary'), leading: Icon(Icons.inbox)),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Social'),
              leading: Icon(Icons.people),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Promotions'),
              leading: Icon(Icons.local_offer),
            ),
            Divider(
              height: 0.1,
            ),
          ],
        ),
      ),
      persistentFooterButtons: <Widget>[
        RaisedButton(
            elevation: 10.0,
            onPressed: () {
              print('lakshmi narayanan');
            },
            color: Colors.orange,
            child: IconButton(
              icon: Icon(Icons.clear),
              onPressed: () {},
            )),
        IconButton(
          icon: Icon(Icons.add),
          color: Colors.yellowAccent,
          onPressed: () {},
        ),
      ],
    );
  }
}*/
/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text(
          'lakshmi narayanana',
          style: TextStyle(color: Colors.tealAccent, fontSize: 10.0),
        ),
        flexibleSpace: SafeArea(
          child: Icon(
            Icons.camera,
            color: Colors.white,
            size: 50.0,
          ),
        ),
        bottom: PreferredSize(
          child: Container(
            color: Colors.yellowAccent,
            height: 56.0,
            width: double.infinity,
            child: Text(
              "lakshmi narayanan",
              style: TextStyle(
                  color: Colors.lime,
                  backgroundColor: Colors.tealAccent,
                  fontSize: 20.0),
            ),
          ),
          preferredSize: Size.fromHeight(75.0),
        ),
        actions: <Widget>[
          Icon(Icons.search),
        ],
      ),
      body: Center(
        child: Text(
          'lakshmi narayanana',
          style: TextStyle(fontSize: 28.0, color: Colors.deepOrange),
        ),
      ),
      floatingActionButton: FloatingActionButton(
        elevation: 10.0,
        child: Icon(Icons.add),
        onPressed: () {
          print('lakshmi narayanan');
        },
      ),
      floatingActionButtonLocation:
      FloatingActionButtonLocation. /*centerDocked*/ centerFloat,
      drawer: Drawer(
        elevation: 16.0,
        child: Column(
          children: <Widget>[
            UserAccountsDrawerHeader(
              accountName: Text('lakshmi narayanan'),
              accountEmail: Text('atechdev360@gmail.com'),
              currentAccountPicture: CircleAvatar(
                  backgroundColor: Colors.white, child: Text('abc')),
            ),
            ListTile(
              title: Text('All Inbox'),
              leading: Icon(Icons.mail),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(title: Text('All Primary'), leading: Icon(Icons.inbox)),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Social'),
              leading: Icon(Icons.people),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Promotions'),
              leading: Icon(Icons.local_offer),
            ),
            Divider(
              height: 0.1,
            ),
          ],
        ),
      ),
      persistentFooterButtons: <Widget>[
        RaisedButton(
          elevation: 10.0,
          onPressed: () {
            print('click');
          },
          color: Colors.deepOrange,
          child: Icon(Icons.add),
        ),
        RaisedButton(
          elevation: 10.0,
          onPressed: () {
            print('click');
          },
          color: Colors.green,
          child: Icon(Icons.clear),
        ),
      ],
    );
  }
}*/
/*import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text(
          'lakshmi narayanana',
          style: TextStyle(color: Colors.tealAccent, fontSize: 10.0),
        ),
        flexibleSpace: SafeArea(
          child: Icon(
            Icons.camera,
            color: Colors.white,
            size: 50.0,
          ),
        ),
        bottom: PreferredSize(
          child: Container(
            color: Colors.yellowAccent,
            height: 56.0,
            width: double.infinity,
            child: Text(
              "lakshmi narayanan",
              style: TextStyle(
                  color: Colors.lime,
                  backgroundColor: Colors.tealAccent,
                  fontSize: 20.0),
            ),
          ),
          preferredSize: Size.fromHeight(75.0),
        ),
        /*actions: <Widget>[
          Icon(Icons.search),
        ],*/
      ),
      body: Container(
        height: 100,
        color: Colors.yellowAccent,
        child: Row(
          mainAxisAlignment: MainAxisAlignment.start,
          crossAxisAlignment: CrossAxisAlignment.stretch,
          children: <Widget>[
            Container(
              color: Colors.red,
              height: 100,
              width: 100,
            ),
            Container(
              color: Colors.green,
              height: 100,
              width: 100,
            ),
            Container(
              color: Colors.orange,
              height: 100,
              width: 100,
            ),
          ],
        ),
      ),
      /*Center(
          child: Text(
        "lakshmi narayanan",
        style: TextStyle(
          fontSize: 25.0,
          color: Colors.lime,
          fontWeight: FontWeight.bold,
          fontStyle: FontStyle.italic,
          letterSpacing: 1.0,
          wordSpacing: 5.0,
          backgroundColor: Colors.orange,
          shadows: [
            Shadow(
              color: Colors.black,
              offset: Offset(4, 4),
              blurRadius: 2,
            )
          ],
          decoration: TextDecoration.underline,
          decorationColor: Colors.red,
          decorationStyle: TextDecorationStyle.double,
        ),
      )),*/
      /*Center(
        child: Text(
          'lakshmi narayanana',
          style: TextStyle(fontSize: 28.0, color: Colors.deepOrange),
        ),
      ),*/

      floatingActionButton: FloatingActionButton(
        elevation: 10.0,
        child: Icon(Icons.add),
        onPressed: () {
          print('lakshmi narayanan');
        },
      ),
      floatingActionButtonLocation:
          FloatingActionButtonLocation. /*centerDocked*/ centerFloat,
      drawer: Drawer(
        elevation: 16.0,
        child: Column(
          children: <Widget>[
            UserAccountsDrawerHeader(
              accountName: Text('lakshmi narayanan'),
              accountEmail: Text('atechdev360@gmail.com'),
              otherAccountsPictures: <Widget>[
                CircleAvatar(
                  backgroundColor: Colors.orange,
                  child: Text('own'),
                )
              ],
              currentAccountPicture: CircleAvatar(
                  backgroundColor: Colors.white, child: Text('abc')),
            ),
            ListTile(
              title: Text('All Inbox'),
              leading: Icon(Icons.mail),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(title: Text('All Primary'), leading: Icon(Icons.inbox)),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Social'),
              leading: Icon(Icons.people),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Promotions'),
              leading: Icon(Icons.local_offer),
            ),
            Divider(
              height: 0.1,
            ),
          ],
        ),
      ),
      persistentFooterButtons: <Widget>[
        RaisedButton(
          elevation: 10.0,
          onPressed: () {
            print('click');
          },
          color: Colors.deepOrange,
          child: Icon(Icons.add),
        ),
        RaisedButton(
          elevation: 10.0,
          onPressed: () {
            print('click');
          },
          color: Colors.green,
          child: Icon(Icons.clear),
        ),
      ],
      endDrawer: Drawer(
        elevation: 16.0,
        child: Column(
          children: <Widget>[
            UserAccountsDrawerHeader(
              accountName: Text('lakshmi narayanan'),
              accountEmail: Text('atechdev360@gmail.com'),
              otherAccountsPictures: <Widget>[
                CircleAvatar(
                  backgroundColor: Colors.orange,
                  child: Text('own'),
                )
              ],
              currentAccountPicture: CircleAvatar(
                  backgroundColor: Colors.white, child: Text('abc')),
            ),
            ListTile(
              title: Text('All Inbox'),
              leading: Icon(Icons.mail),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(title: Text('All Primary'), leading: Icon(Icons.inbox)),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Social'),
              leading: Icon(Icons.people),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Promotions'),
              leading: Icon(Icons.local_offer),
            ),
            Divider(
              height: 0.1,
            ),
          ],
        ),
      ),
      backgroundColor: Colors.teal,
    );
  }
}*/

import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp(
    home: new myapp(),
  ));
}

class myapp extends StatefulWidget {
  @override
  _myappState createState() => _myappState();
}

class _myappState extends State<myapp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text('lakshmi narayanan',
            style: TextStyle(
                color: Colors.tealAccent,
                fontWeight: FontWeight.bold,
                fontStyle: FontStyle.italic,
                fontSize: 10.0)),
        flexibleSpace: SafeArea(
          child: Icon(
            Icons.wifi_calling_sharp,
            color: Colors.yellowAccent,
            size: 50.0,
          ),
        ),
        bottom: PreferredSize(
          child: Container(
            color: Colors.tealAccent,
            height: 70.0,
            width: double.infinity,
            child: Text(
              'lakshmi narayanan',
              style: TextStyle(
                  color: Colors.orange, backgroundColor: Colors.green),
            ),
          ),
          preferredSize: Size.fromHeight(75.0),
        ),
      ),
      body: Center(
        child: Text(
          'lakshmi narayanana',
          style: TextStyle(color: Colors.indigo, fontStyle: FontStyle.italic),
        ),
      ),
      floatingActionButton: FloatingActionButton(
        elevation: 16.0,
        child: Icon(Icons.add),
        onPressed: () {
          print('lakshmi narayanan');
        },
      ),
      floatingActionButtonLocation: FloatingActionButtonLocation.centerFloat,
      drawer: Drawer(
        elevation: 16.0,
        child: Column(
          children: <Widget>[
            UserAccountsDrawerHeader(
              accountName: Text('lakshmi narayanan'),
              accountEmail: Text('atechdev360@gmail.com'),
              currentAccountPicture: CircleAvatar(
                backgroundColor: Colors.white,
                child: Text('abc'),
              ),
            ),
            ListTile(
              title: Text('All Inbox'),
              leading: Icon(Icons.mail),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Starred'),
              leading: Icon(Icons.star),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Snoozed'),
              leading: Icon(Icons.snooze),
            ),
            Divider(
              height: 0.1,
            ),
            ListTile(
              title: Text('Sent'),
              leading: Icon(Icons.send),
            ),
            Divider(
              height: 0.1,
            ),
          ],
        ),
      ),
      persistentFooterButtons: <Widget>[
        RaisedButton(
          elevation: 10.0,
          onPressed: () {
            print('click');
          },
          color: Colors.deepOrange,
          child: Icon(Icons.add),
        ),
        RaisedButton(
          elevation: 10.0,
          onPressed: () {
            print('click');
          },
          color: Colors.green,
          child: Icon(Icons.clear),
        ),
      ],
      bottomNavigationBar: BottomNavigationBar(
        currentIndex: 1,
        fixedColor: Colors.red,
        items: [
          BottomNavigationBarItem(
            // ignore: deprecated_member_use
            title: Text('home'),
            icon: Icon(Icons.add),
          )
        ],
        onTap: (int index) {
          print(index.toString());
        },
      ),
    );
  }
}











import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData(
        // This is the theme of your application.
        //
        // Try running your application with "flutter run". You'll see the
        // application has a blue toolbar. Then, without quitting the app, try
        // changing the primarySwatch below to Colors.green and then invoke
        // "hot reload" (press "r" in the console where you ran "flutter run",
        // or simply save your changes to "hot reload" in a Flutter IDE).
        // Notice that the counter didn't reset back to zero; the application
        // is not restarted.
        primarySwatch: Colors.blue,
        // This makes the visual density adapt to the platform that you run
        // the app on. For desktop platforms, the controls will be smaller and
        // closer together (more dense) than on mobile platforms.
        visualDensity: VisualDensity.adaptivePlatformDensity,
      ),
      home: MyHomePage(title: 'Flutter Demo Home Page'),
    );
  }
}

class MyHomePage extends StatefulWidget {
  MyHomePage({Key key, this.title}) : super(key: key);

  // This widget is the home page of your application. It is stateful, meaning
  // that it has a State object (defined below) that contains fields that affect
  // how it looks.

  // This class is the configuration for the state. It holds the values (in this
  // case the title) provided by the parent (in this case the App widget) and
  // used by the build method of the State. Fields in a Widget subclass are
  // always marked "final".

  final String title;

  @override
  _MyHomePageState createState() => _MyHomePageState();
}

class _MyHomePageState extends State<MyHomePage> {
  int _counter = 0;

  void _incrementCounter() {
    setState(() {
      // This call to setState tells the Flutter framework that something has
      // changed in this State, which causes it to rerun the build method below
      // so that the display can reflect the updated values. If we changed
      // _counter without calling setState(), then the build method would not be
      // called again, and so nothing would appear to happen.
      _counter++;
    });
  }

  @override
  Widget build(BuildContext context) {
    // This method is rerun every time setState is called, for instance as done
    // by the _incrementCounter method above.
    //
    // The Flutter framework has been optimized to make rerunning build methods
    // fast, so that you can just rebuild anything that needs updating rather
    // than having to individually change instances of widgets.
    return Scaffold(
      appBar: AppBar(
        // Here we take the value from the MyHomePage object that was created by
        // the App.build method, and use it to set our appbar title.
        title: Text(widget.title),
      ),
      body: Center(
        // Center is a layout widget. It takes a single child and positions it
        // in the middle of the parent.
        child: Column(
          // Column is also a layout widget. It takes a list of children and
          // arranges them vertically. By default, it sizes itself to fit its
          // children horizontally, and tries to be as tall as its parent.
          //
          // Invoke "debug painting" (press "p" in the console, choose the
          // "Toggle Debug Paint" action from the Flutter Inspector in Android
          // Studio, or the "Toggle Debug Paint" command in Visual Studio Code)
          // to see the wireframe for each widget.
          //
          // Column has various properties to control how it sizes itself and
          // how it positions its children. Here we use mainAxisAlignment to
          // center the children vertically; the main axis here is the vertical
          // axis because Columns are vertical (the cross axis would be
          // horizontal).
          mainAxisAlignment: MainAxisAlignment.center,
          children: <Widget>[
            Text(
              'You have pushed the button this many times:',
            ),
            Text(
              '$_counter',
              style: Theme.of(context).textTheme.headline4,
            ),
          ],
        ),
      ),
      floatingActionButton: FloatingActionButton(
        onPressed: _incrementCounter,
        tooltip: 'Increment',
        child: Icon(Icons.add),
      ), // This trailing comma makes auto-formatting nicer for build methods.
    );
  }
}


