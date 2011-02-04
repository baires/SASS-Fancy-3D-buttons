## SASS Fancy 3D buttons

A very simple but powerfull SASS recipe to create trendy CSS3 buttons.

##Demo

![screenshot](http://files.droplr.com/files/14580855/hJXu.screenshot_04-02-2011_02-15.png)

##Install

Install the buttons module with:

    @import "fancy_3d_buttons";
    
##Configurable Variables

    f3d_button(backgroud color, font size, font weight, line height, border radius, border top, border left)
    
##Mixin

    a.green{
    @include f3d_button(#63bb4a);
    }
    
    a.blue{
    @include f3d_button(#2992DF, 50px, bold, 1.5em, 10px, 2px, 2px);
    }

##Licence

    Copyright (c) 2011 Alexis Sgavel (http://github.com/Baires)
    
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