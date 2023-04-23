# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6



This is a normal text. (Just type it)

This is a **bold text**. (Done using double asterisks)

This is the *italic text*. (Done using single asterisks)

This is the ~~strikethrough text~~. (Done using double tildes)



This is the [link](https://www.google.com). This is done using adding your link text into square bracet and link into normal bracket following square bracket used earlier.

This is an image, it is similar to the links but here you just have to add an exclamation mark before square bracket. Square bracket contain alt text and normal bracket contain a link.
![This is alt text](https://yt3.googleusercontent.com/uB8AMswvMUtYSNm5TcS6ZNhBKBCwhgC5CDE7z87xcxfmiswJ3D0lNSnK11yelj7nWz7AFue2JQ=s900-c-k-c0x00ffffff-no-rj)


Following is ordered list:
1. One
2. Two
3. Three

Lists can work and automatically get corresponding number when you give them just number 1. This helpful when you want to move list items across later.
1. One
1. Two
1. Three

Following is unordered list
- One
- Two
- Three
- These can be nested too, nested links does not work in ordered list.
  - Nested 1
  - Nested 2
  
You can also create a check list using lists.
Square bracket with space means not checked and with x means checked.
These lists can be anything, ordereed or unordered too.
1. [ ] This is not checked ordered list.
2. [x] This is checked ordered list.
- [ ] This is not checked unordered list.
- [x] This is checked unordered list.


Following is the table.
First line must be a column names, columns must be sepatated by a "<space>|<space>".
Below that is the alignment, :--- means left aligned,  :---: means center aligned and ---: means right aligned.
| Column 1, Left aligned | Column 2, Center aligned | Column 3, Right aligned |
| :--- | :---:| ---: |
| Row 1, Column 1 | Row 1, Column 2 | Row 1, Column 3 |
| Row 2, Column 1 | Row 2, Column 2 | Row 2, Column 3 |
Columns cannot contain lists!


Following are the code samples in markdown.
This is a in-line code with single backticks `const firstName = "Om";`.
Below is a multiline code example with three backticks:
```
const firstName = "Om";
const lastName = "Londhe";
```
Below is a multiline code example with syntax highlight with three backticks. For syntax highlighting, you have to append the language extension after opening three backticks:
```ts
const firstName = "Om";
const lastName = "Londhe";
```
Below is an example of a difference in code or changes in code with three backticks,
Add "diff" in place of language extension and "-" for line removal and "+" for line addition:
```diff
- const firstName = "Om";
+ const firstName = "Bhargavi";
const lastName = "Londhe";
```

Following is an example of quote, you can add a quote by just adding a greater than sign and &gt; and a space after that.
> This is a quote.
This is a normal text below quote but as no line break is given, it is merging in quote.

Now this is out of quote, as I have given a line break.


Following is a comment, it will not be visible as it is comment.
<!-- This is a comment -->
Comments start with &lt;!-- and ends with --&gt;, similar to HTML.



For showing TLDRs, you can use HTML details tag.
<details>
  <summary>This is a summary, click to see more</summary>
  This is the text that was hidden and not shown to you as this is the details element.
  
  ![Me and Luffy](https://i.ytimg.com/vi/21cK2auZKV8/hq720_2.jpg?sqp=-oaymwEkCJUDENAFSFryq4qpAxYIARUAAAAAJQAAyEI9AICiQ3gB0AEB&rs=AOn4CLBofQDdxFEFOZClP2VXUSBh6-llUg)
</details>

You can use HTML in the markdown as well, directly use HTML tags and all related stuff!
You can also use some pre-built codes too, just copy-paste the markdown for it and customize it according to your needs.
