For many days I wanted to start a blog site. But due to my good grasp on procrastination, I cannot but start it. But in the last few days, I got a good push to start a new blog. So I went up, sat in front of my PC and went to [GoDaddy.com](https://www.godaddy.com/). And I found the www.dipta007.com available :D. I used my last two days to set up the WordPress blog. And now it is somewhat completed. I will write another post about it another time.

Whatever, to start a new blog, at the first I need to write posts. And for that, the easiest way was to learn markdown language which is used in Github README.md. `.md` extension stands for MarkDown. So I spent an evening to learn that. And this blog is regarding it. It will be a really compressed list of markdown syntaxes. If you want a more detailed overview, follow on the reference links at the end of this post.

<!--more-->

Markdown is somehow like HTML. You will use some syntax and it will render the page according to the specified commands. But the pros of markdown over HTML is that it is more human-readable and can be learnt under 10-20 minutes. Most of the syntaxes are self-explanatory. If you found anything tough to understand, please comment. I will edit the post with more details.

## 1. Bold
Syntax | Result
--- | ---  
\*\*Bold\*\* | **Bold**
\*\*This is a bold sentence\*\* | **This is a bold sentence**

## 2. Italic
Syntax | Result
--- | ---  
\*Italic\* | *Italic*
\*This is an italic sentence\* | *This is an italic sentence*

## 3. Italic and Bold
Syntax | Result
--- | ---  
\*\*\*Bold & Italic\*\*\* | ***Bold & Italic***
\*This is a bold & \*italic\* sentence\* | **This is a bold & *italic* sentence**

## 4. Blockquote

#### Syntax
```
> This is a block quote sentence.  
and it can be multiline.
```
#### Result
> This is a block quote sentence.  
and it can be multiline.

## 5. Inline quote
Syntax | Result
--- | ---  
I know \`this is inline quote\`. can you see it? | I know `this is inline quote`. can you see it?

## 6. Code

#### Syntax

>\```python
def func() {
    a = 1, b = 3
    return a + b
}
\```

#### Result
```python
def func() {
    a = 1, b = 3
    return a + b
}
```

## 7. Horizontal line
#### Syntax   
```
---
```
#### Result  
---

## 8. Newline

For newline, you have to use two whitespaces at the end of the line. (it's weird, I know 😜 )

## 9. Heading
```
# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5  
###### Heading 6  
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6  

## 10. List

* ### Unordered List

    #### Syntax
    Here spaces are replaced with dots
    ```
    * Unordered list1  
    ..* List can be nested too
    ....* More nested
    ```

    #### Result
* Unordered List 1  
  * List can be nested too
        * More nested


* ### Ordered List
    #### Syntax
    ```
    1. Ordered list 1
    2. Ordered list 2
    ```
    #### Result
    1. Ordered list 1
    2. Ordered list 2


## 11. Link

* ### Inline
    Syntax | Result
    --- | ---  
    \[GitHub](https://www.github.com) | [GitHub](https://www.github.com)

* ### Reference
    #### Syntax
    ```
    \[Github]\[1]
    \[1]: https://www.github.com
    ```
    You can specify all the link at the last of the file too

    #### Result
    [Github][1]

    [1]: https://www.github.com

## 12. Embeded Image
* ### Inline
    #### Syntax
    ```
    ![alt text](https://www.logo.com)
    ```
    #### Result
    ![Google Logo](https://cdn4.iconfinder.com/data/icons/new-google-logo-2015/400/new-google-favicon-128.png)

* ### Reference
    #### Syntax
    ```
    ![alt text][logo]
    [logo]: https:/www.logo.com
    ```
    #### Result
    ![Google Logo][logo]

    [logo]: https://cdn4.iconfinder.com/data/icons/new-google-logo-2015/400/new-google-favicon-128.png

## 13. Strikethrough Text
Syntax | Result
--- | ---  
this text is \~~crossed out~~ | this text is ~~crossed out~~

## 14. Task List

#### Syntax
```
[x] Completed
[ ] Not Completed
```

#### Result
[x] Completed
[ ] Not Completed

## 15. Table

#### Syntax
Colon( : ) is used to align row
```
| Table | are | cool           |
| ----- |:---:| ---------------:
| col2  | is  | center aligned |
| col3  | is  | right aligned  |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.
```

#### Result
| Table | are | cool           |
| ----- |:---:| ---------------:
| col2  | is  | center aligned |
| col3  | is  | right aligned  |

## 16. Emojis
[Emoji list](https://gist.github.com/rxaviers/7360908)

## References
* [10 minutes tutorial](https://www.markdowntutorial.com/)
* [Github Official Guide](https://guides.github.com/features/mastering-markdown/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Online Markdown Editor](https://dillinger.io/)
