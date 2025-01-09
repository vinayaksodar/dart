# Heading

**Markdown code:**
```markdown
#Heading
##Subheading
```
## Paragraph

To go to the next line, use two spaces followed by Enter(↩) 

Go to the next paragraph by pressing Enter twice.

**bold text**  
*italicized text*  
***bold and italic***  
~~strikethrough~~  
text <sub>subscript</sub> <sup>superscript</sup>  
underline <ins>text</ins>
>block quote


**Markdown code:**

```markdown
**bold text**  
*italicized text*  
***bold and italic***  
~~strikethrough~~  
text <sub>subscript</sub> <sup>superscript</sup>  
underline <ins>text</ins>
>block quote
```
### Lists 
Ordered list
1. First item
2. Second item

**Markdown code:**
```markdown
Ordered list
1. First item
2. Second item
```

Unordered list
- item
- another item
    - sub item

**Markdown code:**
```markdown
Unordered list
- item
- another item
     - sub item
```


Horizontal rule
---
**Markdown code:**
```markdown
---
```
Horizontal rule automatically makes the text above it subheading

## Code

Use \`  to embed code or command inline `print("hello")`  
Multiline code uses \`\`\`  to embed code blocks like below
```
git status
git add
git commit
```
**Markdown code:**
````markdown
```
git status
git add
git commit
```
````

you can also use tab to indent and embed multiline raw code

    git status
    git add
    git commit

**Markdown code:**
```markdown
    git status
    git add
    git commit

```

Use syntax highlighting in multiline code by specifying the language 
```dart
void main(){
    print("Highlighted code");
}
```

**Markdown code:**
````markdown
```dart
void main(){
    print("Highlighted code");
}
```
````

## Comment in markdown
```
<!-- Comment text >
```

## Table
 

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

**Markdown code:**
```markdown
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
```

<details>
<summary> Collapsed section</summary>
Text in this section is collapsed.Optionally, to make the section display as open by default, add the open attribute to the tag &lt;details open&gt;.

**Markdown code:**
```markdown
<details>
<summary> Collapsed section</summary>
Text in this section is collapsed.Optionally, to make the section display as open by default, add the open attribute to the tag &lt;details open&gt;.
</details>
```

</details>

## Links
1. Random image link [Lorem picsum](https://picsum.photos/200/300)  
**Markdown code:**
`[Lorem picsum](https://picsum.photos/200/300)`

2. Embed image like below

    ![Random image](https://picsum.photos/200/300)  

    **Markdown code:**`![Random image](https://picsum.photos/200/300)`

3. Responsive image for dark and light mode(displays light image or dark image based on selection)
    <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
    <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
    <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
    </picture>

    **Markdown code:**

        <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
        <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
        <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
        </picture>


4. Reference other file in project [README.md](README.md)

    **Markdown code:** 
    
    `[README.md](/README.md)`

    Here / will start path at root of repository not root of computer, read more about how too reference file in other branch or other parts of the repo [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images)

5. Reference heading in something in same document [Table](#table)

    **Markdown code:**
     
    `[Table](#table)`


## Math
Github supports latex read more [here](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)

This sentence uses `$` delimiters to show math inline: $\sqrt{3x-1}+(1+x)^2$

**Markdown code:** 

    This sentence uses `$` delimiters to show math inline: $\sqrt{3x-1}+(1+x)^2$



## VS Code
Use ` Ctrl + Space` for markdown code snippets - very helpful

## References
- [Github flavor markdown](https://github.github.com/gfm/)
- [Github docs about writing](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
- [Markdown in VS Code](https://code.visualstudio.com/Docs/languages/markdown)