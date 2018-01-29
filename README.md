# BeforeAfterJS

## A simple and responsive image comparison slider 

Comparison sliders are nothing new. There are even pure CSS implementations that is nothing but short of amazing. However, I wasn’t able to find a truly responsive one that was simple enough for our needs. This gave me the chance (and excuse) to build one myself that can be used anywhere.


## DEPENDENCIES
- [jQuery](http://jquery.com) for ease

## USAGE

Write this in your html header tag.

    <link rel="stylesheet" href="/assets/BeforeAfter/css/before-after.css"; type="text/css">
<script type="text/javascript" src="/assets/BeforeAfter/js/before-after.min.js"></script>;

Write this in your html body tag bottom.


    <script>$('.ba-slider').beforeAfter();</script>


And write this in your html body tag where you set BeforeAfter slider.

    <div class="ba-slider">
       <img alt="before" src="【beforeの画像パス(URL)】" />
       <div class="resize">
           <img alt="after" src="【afterの画像パス(URL)】" />
       </div>
       <span class="handle"></span>
    </div>

## LICENSE

The MIT License
