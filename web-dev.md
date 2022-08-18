| No. | Sections                                                    |
| --- | ----------------------------------------------------------- |
|     | **Web Developer**                                           |
| 1   | [Overview Of Web Development](#Overview-Of-Web-Development) |
| 2   | [Introduction to HTML](#Introduction-to-HTML)               |
| 3   | [Introduction to CSS](#Introduction-to-CSS)                 |

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

- Opening Tag: Name of the element, wrapped in
- Content: Content of the element

  ```
  <p>This is a element
  </p>

  ```

- Closing Tag: Same as opening tag, but with a /.

3. ### Introduction to CSS

- Cascading Style Sheets
- CSS the (visual and aural) layout, for a variety of devices.
- Consists of countless properties that developers use to format the content: properties about font, text, spacing, layout

# How we select and style elements

- Selectors:

  - h1
  - h2
  - p
  - li
  - etc

- Declaration Blocks:

  ````html
  h1 { color: blue; text-align: center; font-size: 20px } ```
  ````
