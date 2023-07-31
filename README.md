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


