# Array.prototype.toString()

*The toString() method returns a string representing the specified array and its elements.*

The Array object overrides the toString method of Object. For Array objects, the toString method joins the array and returns one string containing each array element separated by commas.

## Syntax

```
        arr.toString();
```

### Return value

A string representing the elements of the array.

## Example 1

The example displays and array of colors. When the method is applied to the array it returns a string of all the colors.

```
        var arr = ['blue', 'red', 'yellow', 'green', 'brown', 'black'];
        arr.toString();
```
The example returns the following string: `"blue,red,yellow,green,brown,black"`

## Example 2 - Complex

Even if the elements of the array are not strings the method converts each one to string. We can see that the array containts different data types.

```
        var arr = ['word', 2, undefined, null, false];
        arr.toString();
```
The example returns the following string: `"word,2,,,false"`. We can see that `undefined` and `null` were converted to an empty string.

## Special Notes

If one of the elements in the array is a function then the `toString()` method will convert the function syntax to a string.

## Browser Support

* Chrome - Yes
* Firefox - Yes
* Internet Explorer - Yes
* Opera - Yes
* Safari - Yes
