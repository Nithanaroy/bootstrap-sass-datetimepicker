Fork of Masanori Ohgita's DateTime picker designed to work with Bootstrap 3, Font-Awesome, and (optionally) Sprockets. Easy to customize.

![screenshot](https://raw.github.com/icambron/jquery-simple-datetimepicker/master/design/dtpicker_screenshot.png)

Details and samples from the original: http://mugifly.github.com/jquery-simple-datetimepicker

I've made a few changes:

 1. Cleaned up appearance to be consistent with Bootstrap 3.
 2. Added SASS variables to make it easy to customize or use in a pipeline.
 3. Added a "dateChanged" event to the JS.

##Using

You have three options:

 1. **Just use the CSS sheet.** Just download it and reference it after Bootstrap and Font-Awesome. This is the simplest option.
 2. **Use it in an asset pipeline along with [bootstrap-sass](https://github.com/thomas-mcdonald/bootstrap-sass/tree/3).** Just grab the [SCSS file](https://raw.github.com/icambron/jquery-simple-datetimepicker/master/sass/jquery-simple-datetimepicker.scss) and `@import` it after Bootstrap. It will inherit many of your Bootstrap customizations and you can also customize the variables directly in the pipeline.
 3. **Customize it and build it**. Just clone the repo, edit the SASS files, and build it (see below). Use the resulting CSS file.
 
## Requirements

* Bootstrap 3
* Font-Awesome (for home icon)
* jQuery 1.7.2 or later

## Building

You'll need Ruby. Run `bundle install` to install SASS. Then run `make`.

Copyright (c) 2013 Masanori Ohgita (http://ohgita.info/), Isaac Cambron.

This program is free software distributed under the terms of the MIT license. 
See LICENSE.txt for details.

