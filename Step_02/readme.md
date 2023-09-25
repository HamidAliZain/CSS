# CSS Properties

Certainly! CSS properties are like instructions for how you want your web page to look. Each property tells the web browser what to do with a specific part of your page. Here are some common CSS properties and what they do in simple terms

## color

Sets the color of the text content

```bash
p {
   color: gray;
 }
```

## font-family

Specifies the typeface or font family for text.

```bash
p {
   color: gray;
   font-family: Arial, sans-serif;
 }
```

## font-size

Sets the size of the text

```bash
p {
    color: gray;
    font-family: Arial, sans-serif;
    font-size: 16px;
 }
```

## font-weight

Controls the thickness or boldness of the text

```bash
p {
    color: yellow;
    font-family: Arial, sans-serif;
    font-size: 16px;
    font-weight: bold;
 }
```

## text-align

Determines the horizontal alignment of text

```bash
p {
    color: purple;
    font-family: Arial, sans-serif;
    font-size: 16px;
    font-weight: bold;
    text-align: center or right or left;
}
```

## line-height

Sets the vertical space between lines of text

```bash
p {
    color: purple;
    font-family: Arial, sans-serif;
    font-size: 16px;
    font-weight: bold;
    text-align: center;/ or right / or left /
    line-height: 1.5;
}
```

## background-color

Defines the background color of an element

```bash
p {
    background-color: black;
}
```

## Margins

The CSS margin properties are used to create space around elements, outside of any element
With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).

1. margin-top
2. margin-right
3. margin-bottom
4. margin-left

```bash
  p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}
```

## Padding

The CSS padding properties are used to generate space around an element's content, inside of any defined borders.
With CSS, you have full control over the padding. There are properties for setting the padding for each side of an element (top, right, bottom, and left).

1. padding-top
2. padding-right
3. padding-bottom
4. padding-left

```bash
  p {
  padding-top: 100px;
  padding-bottom: 100px;
  padding-right: 150px;
  padding-left: 80px;
}
```

## Border

The CSS border properties allow you to specify the style, width, and color of an element's border.

### Border Properties

```bash
  p {
  border-style: dotted; /solid/dashed/double/groove/ridge/inset/outset/none/hidden => more properties
  border-color: blue; => any color
  border-width: 5px;  => define width
  border-radius: 5px; => define radius width
  }
```

### Shorthand Border Property

```bash
p {
  border: 5px solid red;
}
```

## Width and Height

The CSS height and width properties are used to set the height and width of an element.

```bash
div {
  height: 50%;
  width: 50%;
  background-color: powderblue;
}
```

```bash
div {
  height: 500px;
  width: 500px;
  background-color: powderblue;
}
```

## Position Property

The position property specifies the type of positioning method used for an element.
There are five different position values:

1. static
2. relative
3. fixed
4. absolute
5. sticky

```bash
div{
  position: absolute;
  border: 3px solid #73AD21;
}
```

## Box Shadow Property

The CSS box-shadow property is used to apply one or more shadows to an element.

```bash
div {
  box-shadow: 10px 10px lightblue;
}
```
