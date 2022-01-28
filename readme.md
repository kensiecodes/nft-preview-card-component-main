# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](https://github.com/kensiecodes/nft-preview-card-component-main/blob/main/images/NFTfinalss.JPG)



### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/nft-preview-page-completed-xtvea4Y6n)
- Live Site URL: [Vercel](https://nft-preview-card-component-main-six.vercel.app/)

## My process

I always try to round out the full HTML mark-up before ever moving on to CSS. At this point, I'm getting really familiar with how to separate items into divs according to how they will be configured in CSS. I get into the stylesheet fairly quickly and immediately go to change the broader visuals so that I can see everything I'm working with, such as sizing down images. I go in a pretty standard order, biggest to smallest, top to bottom, and this seems to work for me right now on these simpler projects. I tend to write my stylesheet mainly in order of how it appears, and this one was no different.

### Built with

- HTML5
- CSS
- Flexbox
- Mobile-first workflow
- Visual Studio Code


### What I learned
 
While I didn't use it, I learned about *, the all elements selector while picking through documentation. Will be taking note of this for future use. I feel my brain starting to understand the workflow of Flexbox from the markup to stylesheet. 

My major challenge in this project was figuring out the NFT :hover transition. Applying the image AND the color overlay seemed a little daunting at first, but I challenged myself to mess with it without doing any searching. After some finessing, I had my eureka moment:

```css
#imgContainer:hover #overlay {
    opacity:50%;
}
```
It didn't occur to me at first to add a :hover selector to one element that activated another element, but this worked seemlessly and tied it together. Really proud of that!


### Continued development

I'm trying to polish my HTML so that it is really efficient and effective. It's my understanding that generally .class selectors are for elements that appear more than once and #id selectors are for specific elements, but I'm still hazy on how they are used in a professional environment and how accurately I'm doing that. Because this is a solo, single-use project, I used all ids. However, I think if you could personalize the elements and this card were one of many, I imagine I'd be using a lot more class selectors. Side note: I was happy to use a span in this project because I rarely find an excuse to use them (seen at cardFooter).



## Author

- Website - [portfolio](https://kensiecodes.github.io/)
- Frontend Mentor - [@kensiecodes](https://www.frontendmentor.io/profile/kensiecodes)

