# Python3 epub reader #

python/curses epub reader. Requires BeautifulSoup.  
Based on https://github.com/rupa/epub  

## Usage ##

    epub [-h] [-d] <epub-file>  

### optional arguments ###
    * -h, --help  show this help message and exit
    * -d, --dump  dump EPUB to text

### Keyboard commands ###
    - Esc/q          - quit  
    - Tab/Left/Right - toggle between TOC and chapter views  
    - TOC view:  
        * Up         - up a line  
        * Down       - down a line  
        * PgUp       - up a page  
        * PgDown     - down a page  
    - Chapter view:  
        * Up         - up a page  
        * Down       - down a page  
        * PgUp       - up a line  
        * PgDown     - down a line  
