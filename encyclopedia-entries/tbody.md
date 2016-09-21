# Encylopedia Entries

## tbody
`<tbody>` is an HTML element that is employed in the following scenario:
1. As a child of a `<table>` element...
2. after any `<caption>`, `<colgroup>`, and `<thead>` elements...

Appropriate content for `<tbody>` includes zero or more `<tr>` elements and script-supporting elements.

*But*... **it cannot be used when**...
no `<tr>` elements are children of the `<table>` element.

Interestingly, [*a `<tbody>` element's **start tag can be omitted** if the first thing inside the `<tbody>` element is a `<tr>` element,*](spec URL) and if the element is not immediately preceded by a `<tbody>` , `<thead>` , or `<tfoot`> element whose end tag has been omitted. 

It is important to note that the start tag cannot be omitted if the element is empty.

Similarly, a `<tbody>` element's end tag can be omitted if the `<tbody>` element is immediately followed by a `<tbody>` or `<tfoot>` element, or if there is no more content in the parent element.

The `<tbody>` element represents a block of rows that consist of a body of data for the parent table element, if the `<tbody>` element has a parent and it is a table.
-----

