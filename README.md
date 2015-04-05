# jekyll-galleria-flickr
A Jekyll plugin to use Galleria.io galleries using it's flickr plugin. (weird) but (awesome)

Add this to your `_config.yml`:

```
galleria:
 theme: 'path to galleria theme .js'
 user_id: 'your flickr user id'
 ```
 
 Use `galleria_flick.rb` using it's liquid tag and repalce `photo_set_id` by your photo set id:
 
 ```
 {% galleria_flick photo_set_id %}
 ```