# SammyGriddy

SammyGriddy is an easy to use, ligh-weight, responsive grid framework. It utilizes the power of Sass to help compile a fully customizable grid system that also feature "smart grids" which calculates column spans automatically based on the amount of columns in a row.

#Installation

- Clone 'git clone https://github.com/samcus/sammygriddy.git'

#Usage
```
<!-- Explicit Grid -->
<section class="sg__container">
  <div class="sg__1-2"><h3>Half</h3></div>
  <div class="sg__1-2"><h3>Half</h3></div>
</section>

<!-- Implicit Grid-->
<section class="sg__container">
  <div class="sg__smart-col"><h4>Third</h4></div>
  <div class="sg__smart-col"><h4>Third</h4></div>
  <div class="sg__smart-col"><h4>Third</h4></div>
</section>
```

### License
```
Copyright (C) 2016 Samuel Custer

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NON-INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
