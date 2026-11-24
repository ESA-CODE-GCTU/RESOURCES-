# HTML Learning Roadmap

> A beginner-friendly, practical guide to learning HTML.

## 1. Introduction

### Learning objectives

By the end of this section, students should be able to explain what HTML is, understand markup languages, and describe the role of HTML in frontend development.

### 1.1 What is a Markup Language?

A markup language uses tags to describe the structure and meaning of content in a document. HTML stands for **HyperText Markup Language**. It is used to structure content displayed in web browsers.

#### Topics to cover

- [ ] Understand what a markup language is.
- [ ] Understand the meaning of HTML and hypertext.
- [ ] Understand the difference between markup and programming languages.
- [ ] Understand how browsers interpret HTML documents.
- [ ] Identify basic HTML tags and elements.

#### Example

```html
<h1>Welcome to my website</h1>
<p>This is my first HTML paragraph.</p>
```

- `<h1>` identifies the main heading.
- `<p>` identifies a paragraph.

#### Practical exercise

- [ ] Create a file named `index.html`.
- [ ] Write a heading containing your name and a paragraph introducing yourself.
- [ ] Open the file in a web browser.

### 1.2 Frontend Development

Frontend development involves building the parts of a website or web application that users see and interact with.

#### Topics to cover

- [ ] Understand what frontend development is.
- [ ] Understand the difference between frontend and backend development.
- [ ] Understand the role of HTML, CSS and JavaScript.
- [ ] Understand how these three technologies work together.

| Technology | Responsibility |
| --- | --- |
| HTML | Structures the content of a webpage. |
| CSS | Controls the appearance and layout. |
| JavaScript | Adds interactivity and dynamic behaviour. |

#### Practical exercise

- [ ] Visit a website and identify its headings, images, links, buttons and forms.
- [ ] Explain which technology structures the content, which styles it, and which can add interactivity.

### Knowledge check

1. What does HTML stand for?
2. What is a markup language?
3. Why is HTML considered a markup language rather than a general-purpose programming language?
4. What is frontend development?
5. What are the responsibilities of HTML, CSS and JavaScript?

### Learning resources

- [HTML Roadmap](https://roadmap.sh/html)
- [MDN — HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN — Learn Web Development](https://developer.mozilla.org/en-US/docs/Learn_web_development)

---

### How the web works

1. What is HTTP?
2. Domain names
3. Hosting
5. DNS
6. Browsers
7. What is SEO

### Your first HTML file

1. Tags and Attributes
2. Case Insensitivity
3. HTML Entities
4. HTML Comments
5. Whitespaces

### Basic Tags

1. !DOCTYPE
2. html
3. body
4. head
5. meta
6. title

### Textual Tags

1. `h1` to `h6` (headings)
2. `p` (paragraph)
3. `hr` (horizontal rule)
4. `br` (line break)
5. `b` / `strong` (bold / strong importance)
6. `i` / `em` (italic / emphasis)
7. `pre` (preformatted text)
8. `mark` (highlighted text)
9. `sub` (subscript)
10. `sup` (superscript)
11. `a` (links)

### Grouping Tags

1. `div` (block-level container)
2. `span` (inline container)
3. `section` (thematic section of a page)

### Standard Attributes

1. `id`
2. `class`
3. `style`
4. `data-*` (data attributes)

### Table Tags

1. `table` (creates the table)
   - `caption` (title of the table)
   - `thead` (groups the header rows)
   - `tbody` (groups the main body rows)
   - `tfoot` (groups the footer rows, e.g. totals)
   - `tr` (table row)
     - `th` (header cell)
     - `td` (data cell)
   - `colgroup` (groups columns for styling)
     - `col` (a single column inside `colgroup`)
2. Table cell attributes
   - `colspan` (makes a cell span several columns)
   - `rowspan` (makes a cell span several rows)
   - `scope` (tells screen readers whether a `th` heads a row or a column)

### Lists and Types

1. `ul` (unordered list, shown with bullets)
   - `li` (list item)
2. `ol` (ordered list, shown with numbers or letters)
   - `li` (list item)
   - `type` attribute (`1`, `A`, `a`, `I`, `i`)
   - `start` attribute (number to start counting from)
   - `reversed` attribute (counts down instead of up)
3. `dl` (description list, for terms and their definitions)
   - `dt` (term)
   - `dd` (description of the term)
4. Nested lists (a list inside an `li`)

### Embedding Media

1. `img` (image)
   - `src`, `alt`, `width`, `height`, `loading="lazy"`
2. `figure` (groups media with a caption)
   - `figcaption` (caption for the figure)
3. `audio` (sound)
   - `controls`, `autoplay`, `loop`, `muted`
   - `source` (lets you offer several file formats)
4. `video` (video)
   - `controls`, `autoplay`, `loop`, `muted`, `poster`
   - `source` (lets you offer several file formats)
   - `track` (subtitles and captions)
5. `iframe` (embeds another web page, e.g. a YouTube video or Google Map)
6. `picture` (shows different images for different screen sizes)
   - `source`
   - `img`
7. Content Security Policy (CSP) for media
   - What CSP is (a security rule that controls which sites your page may load content from)
   - Setting CSP with `<meta http-equiv="Content-Security-Policy" content="...">` or an HTTP header
   - `img-src` (allowed sources for images)
   - `media-src` (allowed sources for `audio` and `video`)
   - `frame-src` (allowed sources for `iframe`)
   - `object-src 'none'` (blocks old plugins such as Flash)
   - Example: `<meta http-equiv="Content-Security-Policy" content="img-src 'self' https://images.example.com; frame-src https://www.youtube.com">`
8. Safe `iframe` attributes
   - `sandbox` (limits what the embedded page can do)
   - `allow` (grants specific features, e.g. `fullscreen`)
   - `referrerpolicy` (controls what information is sent to the embedded site)

### Using Forms

1. `form` (wraps all the form controls)
   - `action` (where the data is sent)
   - `method` (`get` or `post`)
2. `label` (text that describes an input; linked with `for` and `id`)
3. `input` (single-line input field)
   - Types: `text`, `email`, `password`, `number`, `tel`, `url`, `date`, `checkbox`, `radio`, `file`, `range`, `color`, `hidden`, `submit`, `reset`
   - Attributes: `name`, `value`, `placeholder`
4. `textarea` (multi-line text input)
5. `select` (dropdown list)
   - `option` (one choice in the list)
   - `optgroup` (groups related options)
6. `button` (`type="submit"`, `type="reset"` or `type="button"`)
7. `fieldset` (groups related fields)
   - `legend` (title of the group)
8. `datalist` (suggestions shown while typing in an `input`)
9. Validation attributes
   - `required`, `minlength`, `maxlength`, `min`, `max`, `pattern`

### Semantic Markup

1. What semantic HTML is (tags that describe the meaning of the content, not just how it looks)
2. Why it matters
   - Accessibility (screen readers understand the page structure)
   - SEO (search engines understand the content better)
   - Readable, easier-to-maintain code
3. Page layout tags
   - `header` (top of the page or of a section: logo, title, intro)
   - `nav` (main navigation links)
   - `main` (the main content; only one per page)
   - `section` (a themed group of content, usually with a heading)
   - `article` (self-contained content, e.g. a blog post or news story)
   - `aside` (side content, e.g. a sidebar or related links)
   - `footer` (bottom of the page or of a section: copyright, contact)
4. Text-level semantic tags
   - `strong` vs `b`, `em` vs `i`
   - `time` (dates and times, with a `datetime` attribute)
   - `address` (contact information)
   - `abbr` (abbreviations, with a `title` attribute)
   - `blockquote` and `q` (long and short quotations)
   - `cite` (title of a creative work)
   - `code` (a piece of computer code)
   - `figure` and `figcaption` (media with a caption)
   - `details` and `summary` (content that can be shown or hidden)
5. Semantic vs non-semantic tags (`div`/`span` vs `section`/`article`)
6. Correct heading order (one `h1`, then `h2`, `h3` without skipping levels)
7. Example layout

```html
<body>
  <header>
    <h1>My Blog</h1>
    <nav>
      <a href="/">Home</a>
      <a href="/about">About</a>
    </nav>
  </header>

  <main>
    <article>
      <h2>Learning HTML</h2>
      <p>Published on <time datetime="2026-11-24">24 November 2026</time></p>
      <p>Semantic HTML makes pages easier to understand.</p>
    </article>

    <aside>
      <h2>Related posts</h2>
    </aside>
  </main>

  <footer>
    <p>&copy; 2026 My Blog</p>
  </footer>
</body>
```
