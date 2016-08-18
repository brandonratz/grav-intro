---
process:
  markdown: true
  twig: true
---

# Examples

### Linking - Slug Relative

Link to the path ```pages/01.home/default.md``` using the directory name

<pre>
[Link back home](../home)
</pre>
[Link back home](../home)

***

Link to the path ```pages/01.about/default.md``` using the slug
<pre>
[Link to About](../about/about-grav)
</pre>
[Link to About](../about/about-grav)

### Link Attributes
Values passed as url arguments are converted to attributes - ```?classes=button&target=_blank```

<pre>
[Button](../about?classes=button&target=_blank)
</pre>

[Button](../about?classes=button&target=_blank)

### Image Links

**Remote Image** - ```![Remote Image Example](http://i.giphy.com/nGMnDqebzDcfm.gif)```

![Remote Image Example](http://i.giphy.com/nGMnDqebzDcfm.gif)

**Local Image** - ```![Local Image Example](/images/nGMnDqebzDcfm.gif)```

![Local Image Example](../images/nGMnDqebzDcfm.gif)

**Local Image** - ```![Local Image Cropped](/images/ancient-aliens.jpg?cropResize=100,100)```

Cropping and many other

![Local Image Cropped](/images/ancient-aliens.jpg?lightbox=600,600&resize=100,100)
![Local Image Cropped](/images/ancient-aliens.jpg?cropResize=200,200)
![Local Image Cropped](/images/ancient-aliens.jpg?cropResize=300,300)
