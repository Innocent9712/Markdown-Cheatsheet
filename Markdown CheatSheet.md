# My Markdown CheatSheet


## Headers
---

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

## Horizontal Rules

---

## Paragraph Line Spacing
---

Here's a paragrah I need to break here

Okay it's broken now, after a line in-between.

## Bold and Italics
---

*Here's an italic text* or
_Here's an italic text_

**Here's a bold text** or
__Here's a bold text__

***Here's a bold and italic text***

## Lists
---
### Ordered list
1. item 1
1. item 2
1. item 3
1. item 4

### Unordered list
- item 1
- item 2
- item 3
- item 4

## Code Formatting
---

Inline: Here's a code that I want `this()` formatted.

Fenced code blocks:
```js
const codeBlock = (params) => {
    let note ="Here's a code block that I need displayed"
    return console.log(note)
}
```
PS: you can append the language you need it in, for syntax highlighting.

## Blockquote
---

> This a blockquote,
>
> A multiline blockquote.
>
>> With an indented Blockquote.

## Links
---

### External Links
[Innocent's Portfolio](https://iaminnocent.tech "My Portfolio Link")

### Internal Links
[Link to Headers](#headers)

### Reference Links
Attached to [this][google] is a reference to google link. Reference links are used in situations where you make use of a particular link in multiple places.

[google]: https://google.com "google homepage"

## Images
---

### Image
>![alt text goes here](image src here)

### Image with link
>[![alt text goes here](image src here)][url here]


# Extended Syntax of Markdown

Note: Some of these may not work in vs code but they work on github.

## Table
---

> :--- = left align in a column

> :---: = center align in a column

> ---: = right align in a column

| Packages  | Description   |Versions   |
|:---      |:---:  |---:  |
|React  |Javascript Framework   |v1.0.0 |
|NextJs |React Framework    |v12.2  |

## Task List
---

> Put a __space__ in the bracket if the task is not complete and an __x__ if it is.

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

_Install __Markdown All in One__ vscode extension to see this in action._

## Emojis
---

To use this, checkout github's list of emojis and apply them like this:
> :emoji-name:

_Install __Emoji__ vscode extension to see this in action._

## Comments
---

[This is a hidden comment.]: #

> I wrote a comment but you can't see it, obviously.

## Toggle
---

<details>
    <summary> This is a toggle </summary>
    Actually, I really didn't have anything to say. So, as you were.
</details>


## Callouts
---

> :bulb: __Tip:__ Here's an important tip!


[To add a table of content, open the command pallet "F1" or "Ctrl+shift+P", search for "table of content", which comes from the Markdown all in one extension, and click. Then edit the templet to your taste.
]: #

[If you have an image and you want to specify the display depending on if github is on light or dark mode, add "#gh-mode-name-only". e.g /img/logo.svg#gh-light-mode-only]: #

[For a linked image, add it to the link and not the image url]: #

[Checkout Shields.io for badges]: #
[Checkout feather icons for svg images]: #
[Checkout dev icons for language icons]: #
[Checkout dev icons for language icons]: #


