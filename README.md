# autopxls - random mod
This fork version is selecting random random pixel instead of first available one on left-to-right up-to-down basis like the original does. That way you see the shape of your project faster and script is harder to block, especially if ran by more people.
## Options
Append the option text into URL after the `#`, script checks if it contains the string. Alternatively you can set options like `document.optionname = true;`. List of available options:

>**nostats** - disables stats reporting
>**noautocolor** - disables selecting the closest color on palette if it comes across incorrect one, will just report that in chat and skip like original script if this option is enabled
>**classic** - don't pick random pixel on screen, go line-by-line like the original script
>**fast** - force lower colors check delay = faster drawing, for PXLS with no delay
>**veryfast** - as above, just even faster
>**superfast** - now this is really fast, do not abuse ;)