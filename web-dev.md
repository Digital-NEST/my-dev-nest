| No. | Sections                                                    |
| --- | ----------------------------------------------------------- |
|     | **Web Developer**                                           |
| 1   | [Overview Of Web Development](#Overview-Of-Web-Development) |
| 2   | [Introduction to HTML](#Introduction-to-HTML)               |
| 3   | [Introduction to CSS](#Introduction-to-CSS)                 |
| 4   | [CSS Fundamentals](#CSS-Fundamentals)                       |

## Web Developer

1. ### Overview Of Web Development

> Front-End
> Static Website: Languages that browsers understand: HTML, CSS, JS

- Files: index.html, style.css, script.js, image.jpg

      Example:
        BROWSERS ---Request--->
                <---Response--- WEB SERVER

> Back-End

Dynamic Website: Website files are assembled on the server

      Example:
        BROWSERS ---Request--->
                <---Response--- WEB SERVER -> APP
                                          ↘️   ⬆️
                                           -> DATABASE:
                                                - Nodejs
                                                - PHP
                                                - Python

- HTML ---> Content = Nouns
- CSS ---> Presentation = Adjectives
- JS ---> Dynamic Effects & Web Applications = Verbs

2. ### Introduction to HTML

- Hyper Text Markup Language
- HTML is a markup language that web developers use to structure and describe the content of a webpage (not a programming language)
- HTML consists of elements that describe different types of content: paragraphs, links, images, video, etc.

> Anatomy of an HTML element

👉 Opening tag: Name of the element, wrapped in < and >

👉 Content: Content of the element, in this example text. But it might be another element (child element). Some elements have no content (e.g. <img>)

👉 Closing tag: Same as opening tag, but with a /. When element has no content, it’s omitted

Please read: [html-learning](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

3. ### Introduction to CSS

- Cascading Style Sheets
- CSS the (visual and aural) layout, for a variety of devices.
- Consists of countless properties that developers use to format the content: properties about font, text, spacing, layout

#### How we select and style elements

- Selectors:

- Declaration Blocks:

  ```html
  h1 { color: blue; text-align: center; font-size: 20px }
  ```

- Inside is named {Declaration/ Style}
- color: would be **Property** and blue would be the **Value**

# Working with colors

> The RGB Model : Comming Soon

> Shades of grey : Comming Soon

### CSS Fundamentals

> Resolving Conflicting Declaration

    Highest Priority ->
                     5. Declaration marked !important
                     4. Inline style (style attribute in HTML)
                     3. ID (#) selectors
                     2. Class (.) or pseudo-class (:) selector
                     1. Element selector (p, div, li)
                     0. Universal selector (*)
    Lowest Priority ->

Please Read: [CSS-Learning](https://developer.mozilla.org/en-US/docs/Web/CSS)

Please Watch: [CSS-Watching](https://www.youtube.com/watch?v=JnTPd9G6hoY)
