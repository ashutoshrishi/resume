Preview: http://ashutoshrishi.github.io/CV/

I was not really interested in making a CV in word format. In fact, I
find it easier and faster to write and format a page in HTML than in a
word-like processing software.

So, I wrote my CV in a markdown file: **cv.md**.

Why markdown and not Latex if I wanted a PDF at the end?
--------------------------------------------------------

Simple answer: I am more comfortable with markdown, html and css.

Markdown allows for inserting HTML+CSS in the document. So while most
text bodies are in markdown, HTML tags wrap around it. Plus, I used
the awesome **Bootstrap** project to style the CV. The result is a
clean, but styled, CV which is made using tools I love to use.

The entire process used (in order):

1. Markdown + Bootstrap
2. Pandoc - To convert from markdown to .html
3. WKHTMLTOPDF - To output a pdf from the html file

Lastly, because the CV is never stagnant and needs to improve as I
grow, I put it under version control. Let it increment as I understand
and learn further.

