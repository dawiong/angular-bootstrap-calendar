# Angular Bootstrap Calendar - Modified

## Table of contents

- [About](#about)
- [Modifications](#modifications)
- [License](#licence)

## About

Hi, this plugin is a modified version of mattlewis92's [Angular Bootstrap Calendar] (https://github.com/mattlewis92/angular-bootstrap-calendar).

It's a clone of the source scripts, but I had to edit the templates manually for the
event end times to show in the tooltips and slidedown box for the month view.

The future work I see here, is to provide a configuration for the tooltips and cells.

##Modifications

###Support for Holidays

Events of type 'holiday' will be handled differently. Holiday titles will display on
the cells, will not be marked as event circles, and will not show on the slidebox.

###Modified templates

1. Tooltips Format -> `(08:00 - 09:00) - An event`
2. Slide Box -> `An event - (08:00 - 09:00)`

## License

The MIT License

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
