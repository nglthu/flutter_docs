# DART : Class - Interface - Inheritance <img src='https://nglthu.github.io/flutter_docs/demo/nglthu.png' align='right'> 

# Class
```
class Sinhvien{
    String ten = "Nguyen Lan Anh";
    int tuoi = 19 ;
  
  void showInfo(){
    print(ten);
    print(tuoi);
  }
  void setSinhvien(String setTen, int setTuoi){
    ten = setTen;
    tuoi = setTuoi;
  }

 //Truyen gia tri cho phuong thuc thong qua doi so
  void setSinhvienDoiSo({required String setTen, required int setTuoi}){
    ten = setTen;
    tuoi = setTuoi;
  }

}

void main() {
  
  //Sinhvien sv = new Sinhvien();
  var sv = new Sinhvien();
  sv.showInfo();
  sv.setSinhvien('Nguyen Hoang Manh', 20);
  sv.showInfo(); //Nguyen Hoang Manh 20
  
  
}

```

# Interface
Interface in Dart is Abstract Class
```
//Interface
abstract class  IsLove{
  void love();
  
}
//Class implement for Interface (abstract class)
class LovePerform implements IsLove{
  @override
  void love(){
    print("I Love you");
  }
}
void main() {
  LovePerform lovePer = new LovePerform();
  lovePer.love();
}

```
<img src='demo/interface.png'>

# Inheritance

```
class Shape{
  String hello = "Say hello";
  void cal_area(){
    print("calling caculation of area for Shape");
  }
}
class Circle extends Shape{
  
}
void main() {
  Circle c = new Circle();
  print(c.hello); //Say hello
}

```

# Code (Try Dart) or Flutter App

| Android           | IPhone | Try Dart|
| :---------------- | :------: | ----: |
| <img src='https://nglthu.github.io/flutter_docs/demo/android1.png'> | <img src='https://nglthu.github.io/flutter_docs/demo/iphone.png'>     |  <img src='https://nglthu.github.io/flutter_docs/demo/tryDart2.png'> |

| Web|
| :----------------: | 
| <img src='https://nglthu.github.io/flutter_docs/demo/LearnCode3.png'> | 

## Try Dart
<img src="https://nglthu.github.io/flutter_docs/demo/tryDart.png">

## Android App with Visual Studio Code and Simulatio

<img src="https://nglthu.github.io/flutter_docs/demo/android.png">

## IOS App with XCode and Simulation

Open the folder of IOS on the Xcode

<img src="https://nglthu.github.io/flutter_docs/demo/IOS.png">

<img src="https://nglthu.github.io/flutter_docs/demo/Xcode.png">



# Hanoi, December 2024 <img src='https://nglthu.github.io/flutter_docs/demo/logo.png' align='right'> 
