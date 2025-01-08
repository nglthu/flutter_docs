# DART : Widget Row - Colum <img src='https://nglthu.github.io/flutter_docs/demo/nglthu.png' align='right'> 

# Row
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

# Colum
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
<img src="https://nglthu.github.io/flutter_docs/demo/Interface.png">


# Reference
[Constructor](https://dart.dev/language/constructors)

```
Dart implements many types of constructors. Except for default constructors, these functions use the same name as their class.

+ Generative constructors: Creates new instances and initializes instance variables.

+ Default constructors: Used to create a new instance when a constructor hasn't been specified. It doesn't take arguments and isn't named.

+ Named constructors: Clarifies the purpose of a constructor or allows the creation of multiple constructors for the same class.

+ Constant constructors: Creates instances as compile-type constants.

+ Factory constructors: Either creates a new instance of a subtype or returns an existing instance from cache.
Redirecting constructor: Forwards calls to another constructor in the same class.
```
# Note:

```
Static:

Persist values between instances of a class

It can be accessed without creating an Ojbect
```




# Hanoi, December 2024 <img src='https://nglthu.github.io/flutter_docs/demo/logo.png' align='right'> 

