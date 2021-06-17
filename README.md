# Kirby3 front with Parcel V2

A very basic setup to use ParcelV2 with Kirby3  

1. ```git clone https://github.com/constantinjoly/kirby3-front-with-parcel.git your-new-project```
2. ```cd your-new-project```
3. ```npm install```
4. ```git clone https://github.com/getkirby/kirby.git```
5. Visit ```your-new-project```
6. run: ```npm run dev``` will create the "public" folder with generated css, js files and images. 

## Commands
- ```npm run dev```
- ```npm run build```

## Plugins used:
- autoprefixer
- combine-media-query
- cssnano
- purgecss (will look into templates and snippets php files for classes, ID's and tags, and main.js file)
- critical css (installed not used)

## Parcel docs:
- https://v2.parceljs.org/getting-started/webapp/
- https://v2.parceljs.org/getting-started/migration/

## NB:

Put your images in root of "src" folder

all CSS rules must end with a ```;``` otherwise livereload (sometimes) won't work. You shoud not:
```
.foo{
    color:black
}
```

## What is Kirby CMS
- https://github.com/getkirby
- https://getkirby.com/

## Disclamers
This setup is provided "as is" with no guarantee. Use it at your own risk and always test it yourself before using it in a production environment. 

## License
MIT