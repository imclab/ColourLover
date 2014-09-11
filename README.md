#ColourLover


A simple tool for getting random palette from ColourLover API. This will return a random color palette from the top 50 palettes of ColourLover's selection.

Usage : ColourLovers.getRandomPalette([Scope of your callback function], [callback function]);


##Example : 


<pre><code>ColourLovers.getRandomPalette(this, onColor);

function onColor(colorData) {
  console.log("Colors Hex value : " , colorData.colors)
  console.log("Colors Percentage : " , colorData.colorWidths)
}
</code></pre>
