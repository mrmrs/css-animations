# CSS ANIMATIONS

  Mobile-first classes for css-animations.
  Set the desired css-animations on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-animations
```
View on [npm](https://www.npmjs.org/package/css-animations)


## File Size

1.0K animations.css
850B animations.min.css

## The Code
```
.a-dir-norm {     animation-direction: normal; }
.a-dir-rev {      animation-direction: reverse; }
.a-dir-alt {      animation-direction: alternate; }
.a-dir-alt-rev {  animation-direction: alternate-reverse; }

@media screen and (min-width: 48em) {
  .a-dir-norm-ns {     animation-direction: normal; }
  .a-dir-rev-ns {      animation-direction: reverse; }
  .a-dir-alt-ns {      animation-direction: alternate; }
  .a-dir-alt-rev-ns {  animation-direction: alternate-reverse; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .a-dir-norm-m {     animation-direction: normal; }
  .a-dir-rev-m {      animation-direction: reverse; }
  .a-dir-alt-m {      animation-direction: alternate; }
  .a-dir-alt-rev-m {  animation-direction: alternate-reverse; }
}

@media screen and (min-width: 64em)  {
  .a-dir-norm-l {     animation-direction: normal; }
  .a-dir-rev-l {      animation-direction: reverse; }
  .a-dir-alt-l {      animation-direction: alternate; }
  .a-dir-alt-rev-l {  animation-direction: alternate-reverse; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

