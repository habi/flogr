#flogr
flogr is a php script that will display your public flickr photos in a customizable photo gallery you host on your website. If you use flickr but want to have a different look and feel for your photo gallery you may like flogr. 

Go on and take it for a [spin](http://michael.thecarruthfamily.com/flogr).

##Main Features
- Customizable photoblog interface for your flickr photos
- Display all flickr photos, only photos with certain tags or only certain photosets
- Displays photo details, EXIF data, tags, geo location, and photo comments
- Thumbnail viewer displays photos by date taken, photoset, and tag
- Embedded Slimbox photo slideshow
- Map view of your geo tagged photos
- Flickr tag cloud page
- RSS 2.0 support

##Installation
- Download and unpack the zip locally
- Enter your flickr user id on like 27 of 'admin/config.php'
```php
/**
 * Your Flickr user id and/or group id 
 *
 * Note: A flickr id (not name) is needed.  You can lookup your id at 
 * http://idgettr.com/.
 */
OPTIONAL_SETTING('FLICKR_USER_ID',  '<YOUR-FLICKR-USER-ID');
```
- Upload the zip contents to your webserver (ex. http://foo.com/bar)

##Questions
The best way to get your question answered is the [flogr group](https://groups.google.com/forum/m/#!forum/flogr). 

##Donate
flogr is free to use. Want to share the love? You can by [feeding my caffeine addiction or buying me a beer](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9896181). Thanks!