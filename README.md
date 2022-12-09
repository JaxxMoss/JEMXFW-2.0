# JEMX Frontend CSS Framework
## Version 2.0

I started my first version of a semi-usable frontend CSS framework about a year ago. But since then I learned new stuff! So I decided, like any perfectionist would, screw the old version. I'm gonna start anew!
But I am not perfect. This framework will never be as good as big players in the game like Bootstrap, Foundation and the like. Doesn't mean I won't try. 

So now you know the reason. 
But feel free to leave some constructive criticism! 

Old version: https://github.com/JEMX-mbou/jemxfw

## Naming conventions
When I started working on this framework, I was looking for good naming conventions and file structure. BEM, OOCSS and [SMACSS](http://smacss.com/book) were covered and I decided to implement SMACSS to some extent. 
The basic philosophy is there, but I've extended it a bit. The file structure based on SMACSS can be found in JEMX-v2.0-File-Structure.md (At the time of writing this file is not up-to-date).

The naming conventions of the classes and selectors (also mentioned in the file above) are NOT based on BEM. I am very aware that this is one of the industry standards, but I don't work in industry. I am a teacher. 
This framework is a way for me to keep my skills semi-sharp and have a nice example for my students. 

The main reason for not applying BEM is because I don't see the appeal and advantages to using double underscores. That being said I substitute the double underscores with a single dash. 

I am trying to get the classnames to be as straightforward as they can be. 

**Examples:** 
- .text-left -> text-align: left
- .primary-border -> border-color: *[primary accent color]*
- .banner-content -> *banner-content element. Element used for content in the banner.*


Most of the time I'm trying to use the whole properties or a single key word of the property when it's a utility or a helper class. 
In the case of modules the classnames will consist of module name and part name. 

**Examples:**
- .secondary-background -> background-color: *[secondary accent color]*
- .blend-difference -> mix-blend-mode: difference.
- .banner -> *banner element. Can be used as a full-page banner element.*

*Not all classnames follow the right naming conventions at the moment. Will be updated in the future.*
