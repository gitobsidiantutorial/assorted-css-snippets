# assorted-css-snippets
Snippets that I have made or borrowed and modified for my own use.

[How to use snippets](https://i.imgur.com/aB3eMRn.mp4)

### Contents
- [Image Grids and Floats](#image-grids-and-floats)
- [Kanban](#kanban)
- [Obsidian Tabs](#obsidian-tabs)

## Image Grids and Floats
[Get the snippet](https://raw.githubusercontent.com/gitobsidiantutorial/assorted-css-snippets/main/img-grids-floats.css)

[Demo](https://user-images.githubusercontent.com/81381984/113347719-dde11e80-9335-11eb-9fde-0ae229fed54f.png)


### Description
Credit goes to [lithou](https://github.com/Lithou/Sandbox)

Allows images to be displayed side by side, as well as allowing text to wrap around images. Consider also installing the 

### Usage
When linking to an image, `|grid` makes it display side by side with other images on the same line with the `|grid` marker.

`|left` makes an image float to the left `|right`, to the right, and `|centre` centres an image.

You can still specify an image's width by adding another pipe sign with an image's desired pixel width. `![[Test.png|left|200]]` Embeds an image which allows text to wrap around it, and is 200 pixels wide.

## Left and Right Figcaptions
[Get the snippet](https://raw.githubusercontent.com/gitobsidiantutorial/assorted-css-snippets/main/figcaptions.css)

[Demo](https://i.imgur.com/zY1Gy4g.mp4)
### Description
Extends the Image Floats snippet. Allows a left or right floated image to have a caption beneath it.
### Usage
Insert the following one line break beneath an image.

```markdown
<figcaption id="left/right/centre/center" style="width:200px">CAPTION HERE.</figcaption> 
```
For example:
```markdown
![[example_image.png|left|200]]
<figcaption id="left" style="width:200px">This is a left caption.</figcaption> 
```
Place `left`, `right`, or `centre`/`center` in the id field, depending on the positioning of the image it is paired with. The width of the caption must match the width of image.


## Kanban
[Get the snippet](https://raw.githubusercontent.com/gitobsidiantutorial/assorted-css-snippets/main/kanban.css)

[Demo](https://i.imgur.com/JZQZKKD.mp4)

### Description
Credit goes to Manedblackwolf who created the kanban snippet for her [Spectrum theme](https://github.com/Braweria/Spectrum).

Turns all unordered lists in a designated document into a kanban 'table'. Unindented entries become headers for new columns. Indented children become rows under their parent entries.

Kanbans also allow you to transclude documents side by side.

### Usage
To use kanbans, the following must be at the top of a document. Afterwards, all unordered lists within that document will be turned into kanbans.

```css
---
cssclass: kanban
---
```

## Obsidian tabs
[Get the snippet](https://github.com/gitobsidiantutorial/obsidian-tabs/blob/main/README.md)

### Description
A way to approximate tabs through CSS, including split view. Made for usage in unison with the [pane relief plugin](https://github.com/pjeby/pane-relief).
