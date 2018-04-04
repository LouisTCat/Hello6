# Welcome to the ReadMe for this Project

This ReadMe was authored in Markdown, specifically GitHub Flavored Markdown, which includes syntax highlighting, task lists, tables, and @mentions. (@Name, did I miss anything?) 

Emoji are also supported in Markdown! :thumbsup: :shipit:
See the [Emoji Cheat Sheet](http:http://emoji-cheat-sheet.com) for the complete list.

You can learn more about Markdown here - and you can also create a link automatically like this - https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque in tortor volutpat, tincidunt quam imperdiet, tincidunt felis. Integer ultrices tincidunt nisi, at volutpat lorem bibendum scelerisque. Aliquam quam enim, laoreet sed facilisis vitae, efficitur non tortor. Nam accumsan, nibh non sollicitudin porta, tellus neque faucibus magna, ac varius sapien lacus eget nisl. Suspendisse at erat eu nisi iaculis porta. Nam vulputate, purus in faucibus dignissim, nisl quam vehicula enim, vitae luctus lectus enim a elit. Fusce in enim turpis. Sed sit amet laoreet sapien. Quisque lobortis libero orci, non lobortis massa varius ut. Duis pretium nibh sed erat auctor, eu viverra enim gravida. Phasellus quis aliquam ligula, at interdum lorem. Maecenas efficitur ultrices tristique. Sed nec consequat tortor. Sed at sem lectus. 

## More about Markdown

First, the simple stuff: *This is Italic* **This is Bold**

You can also create unordered lists:

* Item 1
* Item 2
* Item 3

And also ordered lists (of course): 
 
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

## Task Lists

Can be handy to keep track of things to do:

- [x] Task one is done
- [x] Task two is done
- [x] Task three is done
- [ ] This task is not yet done

## Code Blocks

Are easy; just open and close with three backticks.

```javascript
var first
    var name
    first = name = prompt("Enter new name, or OK to end")
    while (name != "" && name != null) {
    	if (name < first)
		first = name
    	name = prompt("Enter new name, or OK to end")
    }
    document.write("

 First name alphabetically = " + first)
