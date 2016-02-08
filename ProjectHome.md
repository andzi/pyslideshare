# Python wrapper for slideshare api #

## Sample Usage ##

```
from pyslideshare import pyslideshare

api_key = '' # Your api key
secret_key = '' # Your secret key

obj = pyslideshare.pyslideshare(locals(), verbose=True)
print obj.get_slideshow(slideshow_id=436333)
```

## Features ##
  * Proxy support
  * Support for downloading presentation from slideshare. (We are the first!)
  * Sample code to get you easily started

## List of methods ##
  * get\_slideshow\_by\_user
  * get\_slideshow
  * get\_slideshow\_by\_tag
  * get\_slideshow\_by\_group
  * upload\_slideshow
  * delete\_slideshow
  * download\_slideshow <sup>New</sup>

help(pyslideshare) should explain you the usage

## Support ##

**Email me** : prabhu dot subramanian at gmail dot com,
**gtalk** : prabhu.subramanian