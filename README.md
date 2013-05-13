Install
-------

Make sure that [ImageMagick](http://www.imagemagick.org/script/index.php) is installed on your system, then:

    git clone https://github.com/danenania/retinize.git
    cd retinize
    sudo chmod u+x retinize 
    sudo cp retinize /usr/bin/

Examples
--------

`retinize some-image.png`

Creates `some-image@2x.png` scaled for retina.

`retinize image1.png image2.jpg`

Creates retina versions with `@2x` appended to each.

`retinize *.png`

Creates retina versions for all png files in directory. Automatically ignores images that have `@2x` in file name. 

`retinize *`

Creates retina version for all png, jpg, jpeg, and gif files in directory. Automatically ignores images that have `@2x` in file name.
