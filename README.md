# Markodwn cheatsheet
>## Headings
Hashtags (#) are used to create headings by putting them before the text of heading.  
It's used like headings from 1 to 6 (h1 - h6) in HTML - the more hashtags (max. 6) before text means smaller text. Heading with just 1 hashtag will have line under it that will seperate    
Text after 6 hashtags is smaller than regular one.  

`Example input:`
```markdown
### Heading with three hashtags
###### Heading with 6 hashtags
Regular text
```
`Output:`
### Heading with three hashtags
###### Heading with 6 hashtags
Regular text  

&nbsp;
>## Images
To display an image, you have to use `![alt-text](path-to-image)`.  
You can't resize an image inside markdown. It's gonna stay that big as it is.  

`Example input:`
```markdown
![markdown-icon](https://cdn.iconscout.com/icon/free/png-256/markdown-2-458334.png)
```
`Output:`  
![markdown-icon](https://cdn.iconscout.com/icon/free/png-256/markdown-2-458334.png)

&nbsp;
>## Links
Links are texts redirecting you to other website or file when you click them.  
For example - [that's text link that leads to GitHub](https://github.com).  
`Example input:`
```markdown
[Google search engine](https://google.com)
```
`Output:`  
[Google search engine](https://google.com)  

&nbsp;
>## Styling text
In markdown you can make text **bold**, _italicized_ or turn it into quote.  

`Example input:`
```markdown
**Bold text**  
_Italicized text_
>Quote
```
`Output:`  

**Bold text**  
_Italicized text_  
>Quote  

&nbsp;  
>## Code blocks
Code blocks are fields of text that contains code with ability to `syntax highlighting` if you will specify what programming or markup language is this.  
To declare code block, you have to use ` ``` ` twice and at the end of first one you put language's name.    

`Example input:`
```markdown
```python
print("Hello World!")
`​`​`
```markdown
# Big heading
`​`​`
```
`Output:`
```python
print("Hello World!")
```
```markdown
# Big heading
```  

&nbsp;
>## Lists
List is set of items written one by one in given order.  
To create one in markdown, you have to put number and dot (markdown will put numbers in order so you don't have to) before and item of list or 4 spaces before subitem in list.  

Example of list:  
1. First item
    1. Something inside 1st item
2. Second item
3. Third item
    1. A
    2. B
    3. C

`Example input:`
```
1. Colors
    1. Red
    1. Green
    1. Blue
2. Obstacles
    1. Square
    1. Triangle
3. Fruits
    1. Cherry
    2. Banana
    3. Watermelon
    4. Apple
4. Empty item
```
`Output:`
1. Colors
    1. Red
    1. Green
    1. Blue
2. Obstacles
    1. Square
    1. Triangle
3. Fruits
    1. Cherry
    2. Banana
    3. Watermelon
    4. Apple
4. Empty item
