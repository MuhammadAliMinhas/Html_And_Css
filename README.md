# Notes

## Heading Tags

When we are using `heading` tags in our website or web pages.We should avoid some **mistakes** : 
1. Dont repeat a `heading` which is already used before some where in the page until, unless you finish using all the headings from **level 1** to **level 6**.

```html
<h1>Hey it's me.....!! Level one heading</h1>
<h1>Another One.....!!</h1>
```
2. We cannot skip any heading, they should be used in sequence.
```html
<h1>i Like heading One</h1>
<h4>blahhh...blahhh...</h4>
```
---
## Paragraph Tags
1. When creating content for our web pages, it is essential to use paragraph tags `<p></p>` to organize and present our information effectively.
2. Avoid using `<br />` tags excessively to break up the entire page content. Instead, opt for employing multiple paragraph tags to create distinct sections.

---
## Void Elements 
We can use the void elements[self-closing-tag-elements] in our code.
1. In Html 5 `<br /> === <br>`.
2. And `<hr /> === <hr>`.

---

## Nested Lists
```html
<h1>Welcome to Optical Iillusions</h1>
    <ul>
      <li>A</li>
      <li>
        B
        <ul>
          <li>Ba</li>
          <li>
            Bb
            <ol>
              <li>Bb1</li>
              <li>Bb2</li>
              <li>Bb3</li>
            </ol>
          </li>
          <li>Bc</li>
        </ul>
      </li>
      <li>C</li>
    </ul>

```
`// Output`

![nestedList](https://github.com/MuhammadAliMinhas/Html_And_Css/assets/113331851/6463833c-6ef9-4d3d-9c92-ad0807d94f70)

---
Another Example of Nested Lists: 

```html
<!-- Write your code below -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>NestedListgoal</title>
  </head>
  <body>
    <ul>
      <li>A</li>
      <li>
        B
        <ol>
          <li>B1</li>
          <li>
            B2
            <ul>
              <li>
                B2a
                <ul>
                  <li>B2aa</li>
                  <li>B2ab</li>
                </ul>
              </li>
              <li>B2b</li>
              <li>B2c</li>
            </ul>
          </li>
          <li>
            B3
            <ol>
              <li>B31</li>
              <li>B32</li>
            </ol>
          </li>
        </ol>
      </li>
      <li>C</li>
    </ul>
  </body>
</html>
```

`// Output `

![AnotherNestedLists](https://github.com/MuhammadAliMinhas/Html_And_Css/assets/113331851/174bbf9b-ff9a-409e-afca-0199c2337a2e)

---
## Image Tag

Images are necessary part of the ___Website___ that makes it look attractive.
We can add images by the src attribute inside the `imag` tag in the ___HTML___.
Lorem Picsum is the website, from where we can add `random` images in our website. Let's dive in to the imag Tag.

```html
<img src="https://picsum.photos/200"alt="Random image "/>
```
`// Output`

![random_Image1](https://github.com/MuhammadAliMinhas/Html_And_Css/assets/113331851/dbdcdee4-e35a-45cc-a51e-5c86a97ae430)

### Some Extra Features:

PicSum Images website provide us the some of the features that can be applied to the images directly through the url. Some of them are as followed : 
- Blur
- Sizing (dynamic Height & Width)
- GrayScaling

Let's apply some of these features on the random images.





