---
title: Python calculator with Tkinter 1
date: 2021-01-03 10:10:10 +530
categories: [Tkinter, Calculator]
tags: [ui, tkinter]
image: 
---
## Introduction
Hey there, today we are talking about ui in Python tkinter so we are going to build a simple calculator it looks like this :

<img src="/assets/img/post_img/calculator.png">

undo and stuff like that will not be done. Because after reading all blogs in this section completely you can do them on your own so don't worry about that.

So first let's talk about tkinter, **tkinter is the standard GUI library for Python. Python when combined with Tkinter provides a fast and easy way to create GUI applications** so this is the short but sweet introduction to tkinter. So for this section **you definitely not need any knowledge about Python** we are going to learn tkinter as well as python so don't worry.


## First gui window
So hurriedly let's jump in to coding for our tkinter app.

The basic tkinter code is like this :
```python
import tkinter as tk
window = tk.Tk()
tk.mainloop()
```

* The basic tkinter code should always be written like this.
* This is the preprosser directive of tkinter.



In python 3.8 it is going to work, what it does is create a simple window of tkinter in linux like this :
<img src="/assets/img/post_img/sample.png">

### Code explained
* `import tkinter as tk` : This line includes tkinter module.   
* 
* `window = tk.Tk()` : Inishalizes the window of tkinter.  
* `tk.mainloop()` : The event loop, it will create a window of tkinter and do like the stuff said before this loop.  

This is all in this blog.   
In next blog on this section we are doing something for our calculator app.  

*If you want to see all blog posts on this section goto categories and open Calculator category in Tkinter category.*