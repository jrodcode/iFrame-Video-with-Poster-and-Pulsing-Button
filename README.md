# iFrame-Video-with-Poster-and-Pulsing-Button
What this Repository does is that it gives the ability to add and image on top of an embedded video. It also has a pulsing button to give it an interactive design.

<h2>How to replace the iframe video?</h2>
<p>Replace the source and then check what kind of features you want at the end of the source, like auto place or display relative videos.</p>

```HTML
<iframe class="videoIframe js-videoIframe" src="https://www.youtube.com/embed/FNPqWao47c0?autoplay=0&rel=0" title="QuietCool What does a whole house fan do?"       frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
```
<h2>How to replace the image?</h2>
<p>All you would have to do is replace the Background-image source and that should do the trick!</p>

```HTML
<button class="videoPoster js-videoPoster" style="background-image:url(https://airsmart.quietcooldealer.com/wp-content/uploads/2022/01/AtticFans.webp);background-size:contain;background-repeat:no-repeat;background-position:center;">
</button>

```
