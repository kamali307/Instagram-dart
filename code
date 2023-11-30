import 'package:flutter/material.dart';
void main()
{
  runApp(const MyApp());
}
class MyApp extends StatelessWidget {
  const MyApp({Key? key}) : super(key: key);
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title:'Instagram',
      home: const Instagrampost(),
    );
  }
}
class Instagrampost extends StatelessWidget {
  const Instagrampost({Key? key}) : super(key: key);
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text('Instagram'),backgroundColor: Colors.pink,),
      body: ListView(
        children:[
          Column(
            children: [
              Row(
                children: [
                  Padding(padding: EdgeInsets.all(10),
                  child: CircleAvatar(
                    radius: 30,
                    backgroundImage: NetworkImage('https://c4.wallpaperflare.com/wallpaper/992/569/313/night-fall-wallpaper-preview.jpg'),
                  ),
                  ),
                  Padding(padding: EdgeInsets.symmetric(horizontal: 7,vertical: 7),
                  child: Column(
                    crossAxisAlignment: CrossAxisAlignment.start,
                    children: [
                      Text('Abi',style: TextStyle(
                        fontWeight: FontWeight.bold,fontSize: 20,
                      ),),
                      Text('Rajapalayam'),
                    ],
                  ),),
                  Spacer(),
                  IconButton(onPressed: (){}, icon: Icon(Icons.more_horiz))
                ],
              ),
              Image(image: NetworkImage('https://images.unsplash.com/photo-1543877087-ebf71fde2be1?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTR8fG5hdHVyYWx8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60')
              ),
              Padding(padding: EdgeInsets.all(7),
              child: Row(
                children: [
                  IconButton(onPressed: (){}, icon: Icon(Icons.favorite_border)),
                  IconButton(onPressed: (){}, icon: Icon(Icons.comment)),
                  IconButton(onPressed: (){}, icon: Icon(Icons.send)),
                  Spacer(),
                  IconButton(onPressed: (){}, icon: Icon(Icons.bookmark_border)),
                ],
              ),),
              Row(
                children: [
                  Stack(
                    children: [
                      Padding(padding: EdgeInsets.symmetric(horizontal: 10),
                        child: CircleAvatar(
                          radius: 30,
                          backgroundImage: NetworkImage('https://wallpapers.net/sky-clearance-hd-wallpaper/download/400x400.jpg'),

                        ),
                      ),

                      Padding(padding: EdgeInsets.symmetric(horizontal: 20),
                        child: CircleAvatar(
                          radius: 30,
                          backgroundImage: NetworkImage('https://wallpapers.net/sea-waves-hd-wallpaper/download/400x400.jpg'),

                        ),
                      ),

                      Padding(padding: EdgeInsets.symmetric(horizontal: 30),
                        child: CircleAvatar(
                          radius: 30,
                          backgroundImage: NetworkImage('https://i.pinimg.com/originals/1d/f5/44/1df5448a99feb276f363d0f7490b2744.jpg'),
                        ),
                      ),
                      Padding(padding: EdgeInsets.symmetric(horizontal: 100,vertical: 10),
                      child: Container(
                        height: 50,
                        width: 190,
                        child: Text('Liked by Ish and other 100000'),
                      ),
                      )
                    ],
                  )
                ],
              ),
              Padding(padding: EdgeInsets.symmetric(horizontal: 30),
              child: Text('Super place and very good memories.... Best place to spend time with friends'),)
            ],
          )
        ]
      )
    );
  }
}
