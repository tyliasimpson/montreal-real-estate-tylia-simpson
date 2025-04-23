# Adding New CSS to the Montreal Real Estate site

1. In your active "Montreal Real Estate" site theme folder, create a new folder called "css".
2. Move the three CSS files from the download folder into the new css folder.
3. Add these three lines of CSS at the top of your style.css stylesheet file. Add them **below** the comment block at the very top of the file.

        @import url(css/mobile-nav.css);
        @import url(css/desktop-nav.css);
        @import url(css/contact.css);


## Why do it this way?

Simply because smaller CSS files are easier to read and manage. Big, long files are more confusing. It also makes understanding which part is "mobile" and which part is "desktop" simpler.