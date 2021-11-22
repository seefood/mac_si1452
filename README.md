# Hebrew Keyboard. is1452-2 for MacOS

In 2016 the new Israeli standards institute published 1452-2, the new standard for Hebrew computer keyboards.
This standard is still not ubiquitous, and some are considering it a bit controvertial (the improved version moved around many letters and symbols) but it was adopted by Microsoft windows very quickly.
Sadly, MacOS still doesn't offer it in 2021, hence this repo.

## Installation instructions

Download the repo as zip (or clone it, your choice). you will see that it has a directory called HebrewKeys.bundle that contains all 3 mappings. You can either copy/move it as is to `${HOME}/Library/Keyboard\ Layouts/` to install it just for yourself or to `/Library/Keyboard\ Layouts/` using `sudo` to install it to all the users of that MacOS machine.

If you don't want the entire bundle, you can copy just one of the layouts as a single file, such as `Hebrew\ si1452-2.keylayout` to the above directories.

## License

[CC0](https://creativecommons.org/share-your-work/public-domain/cc0/), practically public domain.

## References

* [Shachar's page on the standard](https://www.lingnu.com/howto/78-si1452.html) and [lecture](https://www.youtube.com/watch?v=nTtBmNxSohM&ab_channel=OpenSourceIsrael)
* Some background: [Yiddish and Hebrew keyboards on Kann 11](https://www.youtube.com/watch?v=OySK3gHnlkE&ab_channel=%D7%9B%D7%90%D7%9F-%D7%93%D7%99%D7%92%D7%99%D7%98%D7%9C)
* [SII's page (paywall)](https://www.sii.org.il/he/%D7%93%D7%A4%D7%99-%D7%9C%D7%95%D7%91%D7%99/%D7%9B%D7%9C%D7%9C%D7%99/%D7%AA%D7%A7%D7%99%D7%A0%D7%94/%D7%93%D7%A3-%D7%AA%D7%A7%D7%9F/?id=8ecf3b57-b4a6-424e-8d43-11477b8b39ba_HE) and [Draft (free PDF)](https://img.mako.co.il/2016/12/13/mikledet.pdf?Partner=interlink)
* [Wikipedia article](https://he.wikipedia.org/wiki/%D7%9E%D7%A7%D7%9C%D7%93%D7%AA_%D7%A2%D7%91%D7%A8%D7%99%D7%AA#%D7%A4%D7%A8%D7%99%D7%A1%D7%94_%D7%97%D7%93%D7%A9%D7%94)
* [Wikimedia page with lots of details](https://www.mediawiki.org/wiki/Help:Extension:UniversalLanguageSelector/Input_methods/he-standard-2012-extonly/he)
* [interactive map](https://web.archive.org/web/20160303210023/http://webkeys.platonix.co.il/layouts/show/system/si1452/)
* [deprecated solution via keyman, not recommended](https://keyman.com/keyboards/install/basic_kbdhebl3?bcp47=he).

## Changelog

0.1 Initial version POC. Used Ukelele to create an initial Hebrew keyboard (based on the MacOS standard Hebrew) and edited the alt-gr layer to feature Niqqud.

## Todo

* Add "Improved" variant with the 9 new key locations
* Clean up keys mapped to unrelated symbols inherited from original Mac mapping.
