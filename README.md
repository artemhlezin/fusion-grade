# fusion-grade
Grade fuse for Blackmagic Fusion 9

### UI
[![scr1](Screenshots/1.png)]

includes TMI/HSV sliders
[![scr1](Screenshots/2.png)]

### Issues
Not correct gamma calculation if gamma/pixel has negative values.
Usually, you should avoid negative gamma/pixel values. 
I kept the ability to use negative values in gamma
only for TMI sliders compatibility.

### License
MIT
