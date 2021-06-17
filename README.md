# Kirby front with Parcel
1. ```git clone https://github.com/constantinjoly/kirby3-front-with-parcel.git your-new-project```
2. ```cd your-new-project```
3. ```npm install```
4. ```git clone https://github.com/getkirby/kirby.git```
5. Visit ```your-new-project```
6. run: ```npm run dev```

## Commands
- ```npm run dev```
- ```npm run build```

## Plugins used:
- autoprefixer
- combine-media-query
- cssnano
- purgecss (will look into templates and snippets php files for classes, ID's and tags, and main.js file)

## Parcel docs:
- https://v2.parceljs.org/getting-started/webapp/
- https://v2.parceljs.org/getting-started/migration/

## NB:
all CSS rules must end with a ```;``` otherwise livereload will not work. don't:
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