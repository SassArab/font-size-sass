# font-size-sass [![Build Status](https://travis-ci.org/eduardoboucas/include-media.svg?branch=master)](https://travis-ci.org/eduardoboucas/include-media)
> Dynamic font-size in Web site using SASS


## Why?

It is very cumbersome to write the font size in all screen sizes in order to be responsive, so I created this library to help solve this problem somewhat.

## How to install

## How to use
```
@import '../node_modules/font-size-sass/dist/css/fontSize.css'
```
### For Custom 
```
@import '../node_modules/font-size-sass/dist/sass/fontSize.scss'
```
```
# and use this variable with change it value if u need.

$min_width: 320px; // min Screen width
$max_width: 1200px; // max Screen width

$min_font: 16px; // Font-size in min Screen width
$max_font: 28px; // Font-size in max Screen width

```
```
# Then put this in the header of the main style file.

html {
    @include font-size($min_width, $max_width, $min_font, $max_font);
}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## The authors
**font-size-sass** was created by [Ahmed Samir](https://www.facebook.com/ahmed.azam.102)

## License
This project is licensed under the [terms of the MIT license](https://github.com/SassArab/font-size-sass/blob/main/LICENSE.md).
