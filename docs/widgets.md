# DART : Important Widget <img src='https://nglthu.github.io/flutter_docs/demo/nglthu.png' align='right'> 

# Main points in the Layout of multiple widgets vertically and horizontally

```

Row and Column are two of the most commonly used layout patterns.

Row and Column each take a list of child widgets.

A child widget can itself be a Row, Column, or other complex widget.

You can specify how a Row or Column aligns its children, both vertically and horizontally.

You can stretch or constrain specific child widgets.

You can specify how child widgets use the Row's or Column's available space.

```

# Row
<img src="https://nglthu.github.io/flutter_docs/demo/test1.png">

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

<img src="https://nglthu.github.io/flutter_docs/demo/test2.png">

```
Column(
          mainAxisAlignment: MainAxisAlignment.spaceEvenly,
          children: [
            Image.asset('assets/test1.png',
                fit: BoxFit.contain, width: width * 0.95),
            Image.asset('assets/test2.png',
                fit: BoxFit.contain, width: width * 0.95),
          ],
        ),


```

# Demo
## Row layout

<img src="https://nglthu.github.io/flutter_docs/demo/row_columndemo.png">

## Column layout

<img src="https://nglthu.github.io/flutter_docs/demo/android_demo.png" width =250>

# Row Column Layout

## Row Column Axis and CrossAxis

<img src="https://nglthu.github.io/flutter_docs/demo/row_colum_axis.png">

## Layout : Combination

<img src="https://nglthu.github.io/flutter_docs/demo/layout_row_column.png">



```
Container(
          padding: const EdgeInsets.all(20),
          child:
          Row(mainAxisAlignment: MainAxisAlignment.spaceEvenly,
            children: [
            Column(
               mainAxisAlignment: MainAxisAlignment.spaceEvenly,
               children: [
                Image.asset('assets/test1.png',
                fit: BoxFit.contain, width: width * 0.45),
               ]
              
            ),
            Column(
               mainAxisAlignment: MainAxisAlignment.spaceEvenly,
               children: [
                Image.asset('assets/test2.png',
                fit: BoxFit.contain, width: width * 0.45),
               ]
            )
          ],)
        )

```
# Mix layout: Mix between Column and Row

Example :

```
Column(
        mainAxisAlignment: MainAxisAlignment.spaceEvenly,
        children: [
          Row(
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
            children: [
              ClipRRect(
                borderRadius: BorderRadius.circular(8),
                child: Image.network(
                  'https://lethunguyen.github.io/MobileDev/demo/nglthu2.png',
                  width: width * 0.98,
                  fit: BoxFit.cover,
                ),
              ),
            ],
          ),
          Row(
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
            children: [
              Image.asset('assets/layout.png',
                  fit: BoxFit.contain, width: width * 0.90),
            ],
          ),
          Row(mainAxisAlignment: MainAxisAlignment.spaceEvenly, children: [
            Column(mainAxisAlignment: MainAxisAlignment.spaceEvenly, children: [
              Image.asset('assets/test1.png',
                  fit: BoxFit.contain, width: width * 0.7),
              Image.asset('assets/test2.png',
                  fit: BoxFit.contain, width: width * 0.7),
            ]),
            Row(
              mainAxisAlignment: MainAxisAlignment.spaceEvenly,
              children: [
                Text(
                  'Hello 30%',
                  style: TextStyle(
                    fontSize: 32,
                    color: Colors.amber,
                  ),
                )
              ],
            ),
          ]),
        ],
      ),

```
Testing

<img src="https://nglthu.github.io/flutter_docs/demo/mixLayout.png">

# Reference:

[Lay out multiple widgets vertically and horizontally](https://docs.flutter.dev/ui/layout#)

```
Assets folder in the root
configure assets in pubspec.yaml
```




# Hanoi, December 2024 <img src='https://nglthu.github.io/flutter_docs/demo/logo.png' align='right'> 

