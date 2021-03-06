# shitemove (for Firefox)


Replacing estate agent clichés with something a little more truthful.

By Liam Butler (<a href="https://www.twitter.com/AngryFlatCap/">@AngryFlatCap)

Inspired by <a href="http://downworthy.snipe.net/">Downworthy</a> by <a href="https://twitter.com/snipeyhead">Snipe</a>. <a href="https://www.iconfinder.com/icons/299061/house_icon">Logo</a> by <a href="http://www.paomedia.com">Paomedia</a>, with some modifications. Licensed under Creative Commons 3.0.

(This is a quick fix for Firefox compatibility. Eventually I'd like to get this and <a href="https://github.com/liambutler/shitemove">shitemove for Chrome</a> in the same repo, using the WebExtension API)

## What is it?

shitemove is a Chrome plugin, hastily ported to Firefox. When on a property listing it will take words such as 'stunning' and 'stylish' and replace them with words like 'passable' and 'tacky'.

Here are some examples that came up during testing:

![An estate agent listing with altered text. It says 'Cupboard. Winkworth art trying to shift part of an ex-council (meaning someone has made a tidy profit off of this) blog. Accommodation comprises of a separate fully fitted kitchen, a characterless bathroom and a disappointing living/bedroom area.'](/examples/example1.jpg?raw=true)

![An estate agent listing with altered text. It says '1 bedroom flat. SHORT LET. A disappointing and bog-standard one bedroom raised ground floor apartment presented in decidedly average condition throughout and featuring room with high ceiling and access to a lacklustre communal garden.'](/examples/example2.jpg?raw=true)

![An estate agent listing with altered text. It says '1 bedroom flat. Shit one bedroom first floor apartment in shit location'](/examples/example3.jpg?raw=true)

## Visit the website
I've put together an explanatory page over at <a href="http://shitemove.angryflatcap.com">shitemove.angryflatcap.com</a>

## To do

<ul>
  <li>Combine this repo with the <a href="https://github.com/liambutler/shitemove">shitemove for Chrome</a> repo</li>
  <li>Improve the look of the save button on the options screen. I don't like how it's stretching to the width of the div.</li>
  <li>Accessibility improvements.</li>
  <li>Performance enhancements. I don't think that I'm using the MutationObserver API to its full potential at the moment.</li>
</ul>

I haven't been working with HTML and Javascript for that long. If you have any tips on how I can make the interface more accessible or boost the performance, I'd love to hear from you.
