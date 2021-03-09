`<hr>`<br>Most often displayed as a horizontal rule. Used to separate content.<br>
`<br>`<br>Make a line break (a new line)<br>
`<pre>`<br>The text inside it is displayed in a fixed-width font, and it preserves both spaces and line breaks. Example of poems.<br><br>

`<b>`<br>Blod text, without any importance.<br>
`<strong>`<br>Typically displayed in bold,with **strong importance**.<br><br>

`<i>`<br>It defines a part of text in an alternate voice or mood, and it often used to indicate a technical term, a phrase from another language, a thought, a ship name. Typocally displayed in italic. Ex: *sample*<br>
`<em>`<br>It defines emphasized text. Typically displayed in italic. A screen reader will pronounce the words in verbal stress.<br><br>

`<small>`<br>Smaller text.<br>
`<mark>`<br>It defines the text should be marked or highlighted. The content will be yellow in browser.<br>
`<del>`<br>It defines text that has been deleted from a doument. Ex: ~~sample~~<br>
`<ins>`<br>It defines text that has been **inserted into** a document. Browsers will usually underline inserted text.<br>
`<sub>`<br>It defines subscript text. It appears half a character **below** the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O.<br>
`<sup>`<br>It defines superscript text. It appears half a character **above** the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes.<br>
<br>
`<blockquote>`<br>It defines a section that is quoted from another source.Usually use `cite` attribute to specify the source url.<br>
`<q>`<br>It defines a short quotation. Browsers normally insert quotation marks around the quotation. Ex: `<q>sample</q>` would be "sample".<br>
`<abbr>`<br>It defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM". It can give useful information to browsers, translation systems and search-engines. Use `title` attribute to show the abbreviation or acronym.<br>
`<address>`<br>It defines the contact information for the author/owner of a document or an artical. The contact info can be email address, phone number, social media handle(username), etc. The text usually renders in italic, and browsers will always add a line break before and after the element.<br>
`<cite>`<br>It defines the title of a creative work(books, poems, songs, movies, etc.), exclude a person's name. The text usually renders in italic.<br>

## Not-Often-Use
`<bdo>`<br>It used to override the current text direction. Need to using `dir` attribute. If dir="rtl", the text will be writen from right to left. If dir="ltr", the text will be writen from left to right(normally).
## Some little tips
**HTML-Comment**<br>
```
<!-- Comments --> 
or 
<!-- comments 
<p>Sample text</p>
-->
```
## Style Attribute(CSS)
- `style="background-color:Tomato;"`<br>The text background will be Tomato color.
- `style="color:DogerBlue;"`<br>The text color will be DogerBlue.
- `style="border:2px solid Tomato;"`<br>Set the border color.
- `style="font-size:160%;"`<br>The text size will be 160% bigger.
- `style="text-align:center;"`<br>The text will be align to the center.
- `style="border: 2px solid;"`<br>Set the black border.
- `style="padding: 30px;"`<br>It defines a padding(space) between the text and the border.
- `style="margin: 50px;"`<br>It defines a margin(space) outside the border.
## CSS Part
- Inline - by using the style attribute inside HTML elements. Ex: `<p style="color:red;">A red paragraph.</p>`
- Internal - by using a <style> element in the `<head>` section.<br>
Ex:
```
<style>
body {background-color: powderblue;}
h1 {color: blue;}
p {color:red;}
```
- External - by using a <link> element to link to an external CSS file. **Most common way to add CSS**
Ex:
```
<head>
  <link rel="stylesheet" href="style.css">
</head>
```
and the style.css will be: 
```
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
```
