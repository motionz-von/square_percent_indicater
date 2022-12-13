# square_percent_indicater

Flutter package showing progress percent value in square

## Modification

NOTE: This is NOT the official repo for square_percent_indicater.

Source code comes from <https://pub.dev/packages/square_percent_indicater>.
All creadits goes to the original dev.

1. null safety support
2. make width/height optional, in that case, be sure to set a child widget.

## Getting Started

A Ui Package for showing percent progress in a square shape
<p >
<img src="https://i.ibb.co/ThrhP5R/Simulator-Screen-Shot-i-Phone-12-Pro-Max-2021-01-11-at-18-58-12.png" alt="drawing" width="200px" hspace="10"/>
<img src="https://i.ibb.co/4tmmPPx/Simulator-Screen-Shot-i-Phone-12-Pro-Max-2021-01-11-at-18-58-04.png" alt="drawing" width="200px" hspace="10"/>
<img src="https://i.ibb.co/M2xz57h/Simulator-Screen-Shot-i-Phone-12-Pro-Max-2021-01-11-at-18-57-36.png" alt="drawing" width="200px"/>
</p>

## Usage

Just give it values and it will work

## Example

example main.dart is like:

```dart
 SquarePercentIndicator(
          width: 140,
          height: 140,
          startAngle: StartAngle.bottomRight,
          reverse: true,
          borderRadius: 12,
          shadowWidth: 1.5,
          progressWidth: 5,
          shadowColor: Colors.grey,
          progressColor: Colors.blue,
          progress: 0.54,
          child: Center(
              child: Text(
            "54 %",
            style: TextStyle(fontWeight: FontWeight.bold, fontSize: 20),
          )),
        )
```
