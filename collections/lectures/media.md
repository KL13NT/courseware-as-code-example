---
title: Embedding YouTube Videos and Other Media
description: A sample file to show how to embed media in CaC.
---

# Embedding YouTube Videos and Other Media

You can embed YouTube videos and other media in CaC, here is some examples of how it works and how is can be used in CaC.

## Embedding Images

### Inline style

`![alt text](image path or link)`

![cute doggo](https://i.imgur.com/DLE8aXJ.jpg)

![cute doggo gif](https://i.imgur.com/lAG1D7l.gif)

### Reference style

`![alt text][logo]`

`[logo]: image path or link`

![dance][morty dance]

[morty dance]: https://media.tenor.com/JHFfBjUQcxEAAAAC/dance-morty.gif

## Clickable Images

while you can't embed YouTube videos (except using an iframe )directly, you can embed a clickable image that will open the video in a new tab:

`[![alt text](image path or link)](video link)`

[![Piano Cat](https://i.imgur.com/UxsKLea.jpg)](https://www.youtube.com/watch?v=CdEpmU9pRaE)

## Embedding YouTube Videos

### Using Youtube Frame

this is the as clickable images but using the first frame of the video instead of an image:

`[![Image_alt](https://img.youtube.com/vi/<VIDEO_ID>/0.jpg)](https://www.youtube.com/watch/?v=VIDEO_ID)`

`[![image_alt](https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)`

[![image_alt](https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

### Using iframe

<iframe 
width="560" 
height="315" 
src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
title="YouTube video player" frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
allowfullscreen>
</iframe>

## Embedding Audio

### Using links

`[audio name](audio link)`

[audio](https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3)

### Using HTML

`<audio controls> <source src="audio link" type="audio/mpeg"> </audio>`

<audio controls> <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg"> </audio>
