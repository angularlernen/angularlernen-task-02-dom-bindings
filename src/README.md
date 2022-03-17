DOM property and event binding
==============================

### Introduction

Let's interact with the DOM by modifing certain DOM nodes properties and listen to events.

### Task

1. Whenever the user _clicks_ on the profile picture, the image source changes.
2. Whenever the user moves the mouse pointer _into_ the profile picture, the frames color changes.

### HOWTOs

1. Provide two callback _methods_ on your components class: `onMouseEnter()` and `onPictureClicked()`
2. Add to _properties_ to your component class: `frameColor: string` and `pictureUrl: string`
3. In the html markup of the component: bind the properties to the _DOM properties_:

```html
<div [style.backgroundColor]="..."></div>
<img [src]="...">
```
4. In the html markup of the component: bind the callback methods to _DOM events_:


```html
<div (click)="..." (mouseenter)="..."></div>
```
