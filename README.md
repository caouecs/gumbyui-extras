gumbyui-extras
==============

UI modules for [Gumby Framework](https://github.com/GumbyFramework/Gumby).


## Installation

Install via Bower in your Gumby project : 

    bower install gumbyui-extras

or

Clone the GitHub repository, and copy files in your Gumby project

    git clone https://github.com/caouecs/gumbyui-extras.git
    cp -r gumbyui-extras $GUMBY_PROJECTS/sass


You can import all files in your `_all.scss`, or file by file

    @import "(path_to_gumbyui-extras)";

---

## Alert with close

Add the possibility to close an alert box.

### Installation

Import `_alert_with_close.scss` file

### Usage

This module uses the `gumby-trigger:switch`, the value of gumby-trigger must be the same than the id of alert box. You can use id or class.

### Example

    <div class="alert primary" id="alert">
        <a href="#" gumby-trigger="#alert" class="switch close">&times;</a>
        Hello everybody !!!
    </div>

---

## Breadcrumbs

Displays a breadcrumb.

### Installation

Import `_breadcrumbs.scss` file

### Configuration

You can adapt breadcrumb as you want with three variables :

* $breadcrumb-height
* $breadcrumb-border-radius
* breadcrumb-background-color

### Usage

Create a list with class `.breadcrumb`.


### Example

    <ul class="breadcrumb">
        <li><a href="#">Link 1</a></li>
        <li><a href="#">Link 2</a></li>
        <li>Link 3</li>
    </ul>

---

## Colored texts

Adds color to texts.

### Installation

Import `_colored_texts.scss` file

### Configuration

The list of colors is based on *$ui-coloring* from *sass/var/_lists.scss*

### Usage

Add `.text-$color` class with $color in the list of $ui-coloring.

### Example

    <span class="text-primary">I have a beautiful color</span>
    <a href="#" class="text-success">I'm a link and I have a other beautiful color, my :hover too</a>

---

## Tables

Adds visibility to tables.

### Installation

Import `_tables.scss` file

### Configuration

Not yet.

### Usage

Add `.table class` at your tables.

### Example

    <table class="table">
    </table>


---

## Tabs with nav bottom

Displays a tab module with nav at bottom

### Installation

Import `_tabs_bottom.scss` file

### Usage

Add `.tabs-bottom` at your tabs, and define tab-nav after tab-content

### Example

    <div class="tabs tabs-bottom">
        <div class="tabs-content">Blabla 1</div>
        <div class="tabs-content">Blabla 2</div>
        <ul class="tab-nav">
            <li>Link 1</li>
            <li>Link 2</li>
        </ul>
    </div>

---

## Visibility by class

When you want to define visibility directly in html, instant of use *@mixin hidden() and visible()*

### Installation

Import `_visibility_by_class.scss` file

### Usage

Add `.visible-$device` or `.hidden-$device` to display or hidden on a specified device.

List of $device :

* desktop
* tablet
* phone

### Example

    <div class="visible-tablet visible-mobile">
        You can see me on a tablet and mobile
        <span class="hidden-mobile">but I'm hidden on mobile</span>
    </div>

---

MIT Open Source License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.