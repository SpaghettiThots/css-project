
# `<u>`

*The HTML Underline Element (\<u>) renders text with an underline, a line under the baseline of its content.*

In HTML5, this element represents a span of text with an unarticulated, though explicitly rendered, non-textual annotation, such as labeling the text as being a proper name in Chinese text (a Chinese proper name mark), or labeling the text as being misspelled.

## Attributes

This element does not have any self attributes.

## Example

The example below shows the text inside of the `<u>` tag as underlined.

```
        <p>This is a paragraph with an <u>underlined</u> text</p>
```

## Browser Support

All browsers support the `<u>` tag.


# border-bottom-width

*The border-bottom-width CSS property sets the width of the bottom border of a box.*

## Syntax

The `border-bottom-width` property can accept a `<length>` value or one of the following keywords: `thin`, `medium`, `thick` or `inherit`:

```
        background: <length> | thin | medium | thick
```

### Values

#### `<length>`

This value can be specified in different units such as `em`, `px`.

#### thin

Value specifies a thin border.

#### medium

Value specifies a medium border

#### thick

Value specifes a thick border

#### inherit

Value represents a value of `border-bottom-width` of the parent's element.

## Example

In the example we can see different specifications for the `border-bottom-width` property.

```
        element-a {
          border-bottom-width: 5px;
        }
        
        element-b {
          border-bottom-width: 2vmax;
        }
        
        element-c {
          border-bottom-width: 2em;
        }
        
        element-d {
          border-bottom-width: thin;
        }
        
        element-e {
          border-bottom-width: medium;
        }
        
        element-f {
          border-bottom-width: thick;
        }
        
        element-g {
          border-bottom-width: inherit;
        }
```

## Browser support

* Chrome - 1.0+
* Firefox - 1.0+
* Internet Explorer - 4.0+
* Opera - 3.5+
* Safari - 1.0+


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
