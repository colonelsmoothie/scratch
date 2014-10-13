##################### scratch

Just a place for experimental code. I mostly use this to test out git commands (like push and pull), and as a Markdown reference.

## Markdown

Github readme files are, by default, written in [Markdown](http://en.wikipedia.org/wiki/Markdown) (a [markup language](http://en.wikipedia.org/wiki/Markup_language)). Markdown files are ordinary text files that can be used to create web pages - much like html, but simpler. This makes Markdown an ideal language for online readme files since this provides the creator with increased functionality over plain text but without the unnecessary complexity of html, which is designed for full-blown webpages. For users who do want to use webpages for their Github projects, Github pages is also available.


## Headers

A hash sign (\#) is used to denote a header. Markdown allows for up to six levels:

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

These headers were produced via the following code:

    # Header 1
    ## Header 2
    ### Header 3
    #### Header 4
    ##### Header 5
    ###### Header 6
    
## Font Style

You can also **bold text**, *italicize text*, or ***bold and italicize text***:

    You can also **bold text**, *italicize text*, or ***bold and italicize text***

## Lists
.

You can use the dash (\-) symbol to create a list:

- Element 1
 - Element 1.a
     - Element 1.a.i
     - Element 1.a.ii
 - Element 1.b
- Element 2
- Element 3

Or use numbers to create an ordered list:

1. This
2. List
3. Is
4. Ordered

## Links

We can also insert named links. You can go to my github personal page [here](http://colonelsmoothie.github.io/).

    We can also insert named links. You can go to my github personal page [here](http://colonelsmoothie.github.io/).
    
We can furthermore just refer to the link itself. The URL of my page is <http://colonelsmoothie.github.io/>.

    We can furthermore just refer to the link itself. The URL of my page is <http://colonelsmoothie.github.io/>.
    
## Blockquotes

We can use the right-angle bracket (\>) to create a blockquote:

 
> I AM A SICK MAN.... I am a spiteful man. I am an unattractive man. I believe my liver is diseased. However, I know nothing at all about my disease, and do not know for certain what ails me. I don't consult a doctor for it, and never have, though I have a respect for medicine and doctors. Besides, I am extremely superstitious, sufficiently so to respect medicine, anyway (I am well-educated enough not to be superstitious, but I am superstitious). No, I refuse to consult a doctor from spite. That you probably will not understand. Well, I understand it, though. Of course, I can't explain who it is precisely that I am mortifying in this case by my spite: I am perfectly well aware that I cannot "pay out" the doctors by not consulting them; I know better than anyone that by all this I am only injuring myself and no one else. But still, if I don't consult a doctor it is from spite. My liver is bad, well -- let it get worse! 

## Github Flavored Markdown

Github's implementation of Mardown let's us highlight syntax for different languages. For example, here's R:

```r
print("Hello World")
```

Code:

    ```r
    print("Hello World")
    ```
    
That's it! Have a good day!
