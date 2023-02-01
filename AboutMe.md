# Lalith Vuppala
I am from India,hyderabad. I'm a guitarist and love to sing,photography. I have completed my bachelor degree in the stream of Electronic & Communication Engineering.

[link](Snapchat-669521843.jpg)

*******
# Country Table

| Name of the country | Reason                        |Time to spent(DAYS)|
|---------------------|:--------------------------:|----------------:|
| America             | For Master's education                  |2 Years |
| Italy               |To have fun with friends                 |3 months |
| Switzerland |To get experice of the nature(mountains & hills) | 1 month |
| Combodia  | incredible amount of history and culture          | 2months |


******
# Quotes

> Don’t let yesterday take up too much of today. _Lalith_

> Whatever you are, be a good one.  _Lalith_

> Whatever might be the situation never loose you'r slef. _LalithNarayana Vuppala_

********
# Code 

> Preloading images with jQuery

> I'm looking for a quick and easy way to preload images with JQuery.

[link for above question from stack overflow](https://stackoverflow.com/questions/476679/preloading-images-with-jquery)

```javascript

function complexLoad(config, fileNames) {
  for (var x = 0; x < fileNames.length; x++) {
    $("<img>").attr({
      id: fileNames[x],
      src: config.imgDir + fileNames[x] + config.imgFormat,
      title: "The " + fileNames[x] + " nebula"
    }).appendTo("#" + config.imgContainer).css({ display: "none" });
  }
};

```
> answer for above query
```javascript

$.preloadImages = function() {
  for (var i = 0; i < arguments.length; i++) {
    $("<img />").attr("src", arguments[i]);
  }
}

$.preloadImages("hoverimage1.jpg","hoverimage2.jpg");

```
[quick link to code snippt](https://css-tricks.com/snippets/jquery/image-preloader/)



