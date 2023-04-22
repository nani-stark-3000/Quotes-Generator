# Quotes-Generator

## Introduction
This code generates images with quotes and authors. The code takes a csv file with quotes and authors and creates an image with the quote and author on it. The images are saved in a folder named `Quotes`. 

## Dependencies
* pandas
* PIL

## Installation
The code uses `pandas` and `PIL` python libraries. You can install these libraries using the following commands:
```
pip install pandas
pip install pillow
```

## Usage
The code uses a csv file `quotes.csv` to generate images. You can modify this file and add your own quotes and authors. The file should have two columns, one for the quote and the other for the author. If there is no author, then the author column can be left blank.

To generate the images, run the code in any python environment. The images will be saved in a folder named `Quotes`.

The code provides two functions for generating the images:

### draw_text
`draw_text` function generates an image with a given quote and author. It takes the following arguments:
* `quote`: The quote to be written on the image.
* `author`: The author of the quote.
* `img_color`: The background color of the image.
* `font_file_path`: The path of the font file.
* `font_color`: The color of the text.
* `save_path`: The path where the image will be saved.

### text_wrap
`text_wrap` function wraps a long line of text into shorter lines that can fit into the image. It takes the following arguments:
* `text`: The long line of text that needs to be wrapped.
* `font`: The font object that is used for the text.
* `max_width`: The maximum width of the line in the image.

## Sample Output
The code generates images with different background colors and fonts. Some sample images are provided in the `Quotes` folder.
![quote](https://github.com/nani-stark-3000/Quotes-Generator/blob/0766ecb889629623df1a5e0bd55418f8bb78f717/0.png)
