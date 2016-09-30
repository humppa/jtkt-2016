
# jtkt-2016

[jtkt]: https://www.cs.helsinki.fi/courses/582102/2016/s/k/1

Material produced when working on course [Johdatus tietojenkäsittelytieteeseen][jtkt].

To build the slideshow, use `pandoc`(1):

    $ pandoc -t slidy --css hy_style.css -A hy_footer.html <source.md> -o index.html
