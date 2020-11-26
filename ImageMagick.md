## Convert, Resize and Center the Image
convert adobe.jpg -resize 300x100 -background white -gravity center -extent 300x100 output.jpg

## Add border
convert -border 20 -bordercolor white sites.png output.jpg