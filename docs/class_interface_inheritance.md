# DART : Class - Interface - Inheritance
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

# Inheritance

# Code (Try Dart) or Flutter App

## Try Dart
<img src="https://nglthu.github.io/flutter_docs/demo/tryDart.png">

## Current Flutter App

<img src="https://nglthu.github.io/flutter_docs/demo/LearnCode3.png">
