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
