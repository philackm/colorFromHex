# colorFromHex

A simple extension written in Swift for UIColor in UIKit which adds a class function that returns a UIColor from the provided hex string. The colours are cached.

## Usage

Parameters: hexString: String, the hex code for the color you want. Leading "#" is optional. Must be 6 hexadecimal digits long. (8 bits per color)

```let someColor = UIColor.colorFromHex("#2d34aa")```
