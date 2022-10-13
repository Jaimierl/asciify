![](https://github.com/RameshAditya/asciify/blob/master/github-resources/logo.JPG)
# Convert Images into ASCII Art with the power of Python


![](https://github.com/RameshAditya/asciify/blob/master/github-resources/sample.gif)

## Contents
- [What ASCIIFY is](#what-asciify-is)
- [How ASCIIFY works](#how-asciify-works)
- [How to use ASCIIFY](#how-to-use-asciify)
- [Future Plans](#future-plans)
- [Support me](#support-me)

## What ASCIIFY is
ASCIIFY is a python script that takes in as input an image, and returns a text output that resembles the input image.
In other words, it replicates an image with certain characters.

For example, when the following image of Octocat - 
![](https://github.com/RameshAditya/asciify/blob/master/octocat.png)

is passed as a parameter into ASCIIFY, the following output is observed -

```
....................................................................................................
....................................................................................................
.....................................####:...............####.......................................
.....................................#########################......................................
.....................................#########################......................................
.....................................########################.......................................
....................................###########################.....................................
...................................#############################....................................
...................................########?+?#######%++########....................................
...................................#####:::..::::::::::..::+####....................................
...................................####:::....::::::::.?..::####....................................
...................................####:::..?.::::::::?.?.::####....................................
...................................+###:::+??;::::::::???.::@###....................................
....................................###:::.??.::::::::.?..::###.....................................
.......................................###:::::::?::::::::###.......................................
........................................:####::::::::::@###.........................................
..................................###.......############............................................
..................................:,##.......@#######@..............................................
..................................:.##......###########.............................................
.....................................#:;....###########.............................................
......................................#@%#:S#####.#####@............................................
.......................................#######.##.######............................................
............................................##.##.######............................................
............................................##.##.######............................................
........................................::::##:##:######::::........................................
.....................................::::::###:##:###:###::::::.....................................
....................................,:::::::++##S::###++:::::::.....................................
.....................................:::::::++:++:++++++:::::::.....................................
.......................................:::::++:++:++++++:::::.......................................
..........................................::++:++:++++++::..........................................
..................................................,.................................................
....................................................................................................
```
-------------------------------------------------------------------------------------------------------
## How ASCIIFY works
ASCIIFY works in a rather simple and intuitive way.
Here's the algorithm -
- Resize the image to a standard dimension, while maintaining aspect ratio
- Convert to grayscale (the reason for doing so is because characters are replaced based on their intensity)
- Create list of special characters to replace pixels with
- Classify and divide pixels into buckets or groups, based on their intensity
- Replace all pixels in a bucket with the corresponding special character
- Print the text into terminal or write into a file
- Profit!

-------------------------------------------------------------------------------------------------------
## How to use ASCIIFY
- Ensure you have the required dependency "PIL" for Python installed. (pip install pillow)
- Clone the repo
- Run the python script, and pass the image path as the parameter
- The script will print the output in the terminal, and will also write into a file 'img.txt' in the same directory as the python script
- Profit!

-------------------------------------------------------------------------------------------------------
## Future Plans
- Alternatively support colored outputs by printing the text onto an image


-------------------------------------------------------------------------------------------------------
## Color Output Sources

- Pillow <https://pillow.readthedocs.io/en/stable/reference/Image.html?highlight=getdata#PIL.Image.Image.getdata>
- Stack Overflow - Text Color <https://stackoverflow.com/questions/287871/how-do-i-print-colored-text-to-the-terminal>
- Stack Overflow - Iterating through multiple lists <https://stackoverflow.com/questions/1663807/how-do-i-iterate-through-two-lists-in-parallel>

-------------------------------------------------------------------------------------------------------
## Support Me
If you liked this, leave a star! :star:

If you liked this and also liked my other work, be sure to follow me for more! :slightly_smiling_face:
