# DART : Widget Row - Colum <img src='https://nglthu.github.io/flutter_docs/demo/nglthu.png' align='right'> 

# Row
<img src="https://nglthu.github.io/flutter_docs/demo/row.png">

```
body: Row(
        mainAxisAlignment: MainAxisAlignment.spaceEvenly,
        children: [
          Image.asset('assets/test1.png',
          fit: BoxFit.contain,
          width: width* 0.5),
          Image.asset('assets/test2.png',
          fit: BoxFit.contain,
          width: width* 0.5),
          
        ],
      ),
```

# Column
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
<img src="https://nglthu.github.io/flutter_docs/demo/row_columndemo.png">


# Row Column : Axis and CrossAxis


<img src="https://nglthu.github.io/flutter_docs/demo/row_colum_axis.png">

```
Dart implements many types of constructors. Except for default constructors, these functions use the same name as their class.

+ Generative constructors: Creates new instances and initializes instance variables.

+ Default constructors: Used to create a new instance when a constructor hasn't been specified. It doesn't take arguments and isn't named.

+ Named constructors: Clarifies the purpose of a constructor or allows the creation of multiple constructors for the same class.

+ Constant constructors: Creates instances as compile-type constants.

+ Factory constructors: Either creates a new instance of a subtype or returns an existing instance from cache.
Redirecting constructor: Forwards calls to another constructor in the same class.
```
# Reference:

[Lay out multiple widgets vertically and horizontally](https://docs.flutter.dev/ui/layout#)

```
Assets folder in the root
configure assets in pubspec.yaml
```




# Hanoi, December 2024 <img src='https://nglthu.github.io/flutter_docs/demo/logo.png' align='right'> 

