<img src="img/markdown-mark-white.svg" width="100" height="100" background-color="red"> 

# Entended Syntax
 Advanced features that build on the basic Markdown syntx.

### Overview[^1]
The [basic syntax](https://www.markdownguide.org/basic-syntax) outlined in the original Markdown design document added many of the elements needed on a day-to-day basis, but it wasn’t enough for some people. That’s where extended syntax comes in.

Several individuals and organizations took it upon themselves to extend the basic syntax by adding additional elements like tables, code blocks, syntax highlighting, URL auto-linking, and footnotes. These elements can be enabled by using a lightweight markup language that builds upon the basic Markdown syntax, or by adding an extension to a compatible Markdown processor.
### Availability[^2]
 Not all Markdown applications support extended syntax elements. You’ll need to check whether or not the lightweight markup language your application is using supports the extended syntax elements you want to use. If it doesn’t, it may still be possible to enable extensions in your Markdown processor.

### Tables [^3]
    |No. |Syntax | Explaination|
    |--- | :----: |------------ |
    |01  | ** or __   |Use for bold text|
    |02  | * or _   |Use for italic text|
    |02  | #   |Use for heading but following 

Output:
|No. |Syntax | Explaination|
|--- | :----: |------------ |
|01  | ** or __   |Use for bold text|
|02  | * or _   |Use for italic text|
|02  | #   |Use for heading but following <br>Level heading|
<br>


 Tip: Creating tables with hyphens and pipes can be tedious. To speed up the process, try using the [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables) or [AnyWayData Markdown Export](https://anywaydata.com/). Build a table using the graphical interface, and then copy the generated Markdown-formatted text into your file.

### Fenced Code Blocks[^4]
    ```
    {
    "Email" : "Mrr.visal.cf@gmail.com",
    "Nickname" : "Xenn",
    "Gender" : "Male"
    }
    ```
Output:
```
    {
    "Email" : "Mrr.visal.cf@gmail.com",
    "Nickname" : "Xenn",
    "Gender" : "Male"
    }
```
If we want Hightlight code blocks we can use syntax

    ```json
    {
    "Email" : "Mrr.visal.cf@gmail.com",
    "Nickname" : "Xenn",
    "Gender" : "Male"
    }
    ```
Output:

```json
    {
    "Email" : "Mrr.visal.cf@gmail.com",
    "Nickname" : "Xenn",
    "Gender" : "Male"
    }
```


### Fontnotes [^5]
    Here's a simple footnote,[^1] and here's a longer one.[^bignote]

    [^1]: This is the first footnote.

    [^bignote]: Here's one with multiple paragraphs and code.

        Indent paragraphs to include them in the footnote.

        `{ my code }`

        Add as many paragraphs as you like.

Output:

This is the first footnote. ↩

Here’s one with multiple paragraphs and code.

Indent paragraphs to include them in the footnote.

{ my code }

Add as many paragraphs as you like. ↩

### Heading IDs [^6]

    ### My ID Creating {#my-id}

The Html look like:

    <h3 id="my-id">My ID Creating</h3>

### Definition Lists [^7]

    First Term
    : This is the definition of the first term.

    Second Term
    : This is one definition of the second term.
    : This is another definition of the second term.

Output:

First Term
    : This is the definition of the first term.

Second Term
    : This is one definition of the second term.
    : This is another definition of the second term.
### Strikethrough [^8]
    ~~Live isn't easy like everyone expexcted~~

Output
~~Live isn't easy like everyone expexcted~~

### Task Lists[^9]

    - [ ] Check 1
    - [ ] Check 2
    - [ ] Check 3

Output:
- [ ] Check 1
- [ ] Check 2
- [ ] Check 3

### Emoji[^10]

    I have plans for camping next month :wink:

Output:

 I have plans for camping next month :wink:

### Hightlight[^11]

    I ==had spent== many hour for waiting on you. 
    This sentence show about happened in the past

Output:
I ==had spent== many hour for waiting on you. 
    This sentence show about happened in the past

### Subscript[^12]
    H~2~SO~4~
    A^2^+B^2^=A^2^+2AB+B^2^
Output:

H~2~SO~4~
A^2^+B^2^=A^2^+2AB+B^2^

### Automatic URL Linking And Disable [^13]

    https://www.markdownguide.org
Output:
https://www.markdownguide.org

if we wanna disable we use backtick

    `https://www.markdownguide.org`
Output:
`https://www.markdownguide.org`

[^1]: Overview
[^2]: Availability
[^3]: Tables
[^4]: Fenced Cold Blocks
[^5]: Fontnotes
[^6]: Heading IDs
[^7]: Definition Lists
[^8]: Strikethrough
[^9]: Task Lists
[^10]: Emoji
[^11]: Hightlight
[^12]: Subscript
[^13]: Automatic URL Linking And Disable



