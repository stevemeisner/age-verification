age-verification
================

Simple cookie based age verification using jQuery

## Requirements

* [jQuery](http://jquery.com/)
* [jquery.cookie](https://github.com/carhartl/jquery-cookie)

***

I developed this to be implimented on a lightly customized Squarespace site in which we could only paste in custom JS or CSS.

In the demo I've put the neccesary JS and CSS into external files but for something like a Squarespace implimentation, you would need to simply paste the contents of the CSS and JS files into the space provided by the system.

You can see where to inject the JS from this helpful [Squarespace Article](https://support.squarespace.com/hc/en-us/articles/205815908).

### To use your own logo...

Simply edit line 39 of `age-verification.css` where is says `background-image: url(data:image/svg+xml;base64,PD9...)` to be `background-image: url(path/to-your-/image)`.

### Contributors

* [Sebastien Gens](https://github.com/SebastienGens)
