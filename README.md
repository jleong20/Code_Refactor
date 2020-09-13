# Horiseon Homepage

## Description

A webpage plays a pivotal role in providing **descriptive** information about your product, and so should 
the HTML written to display this webpage. My goal for this webpage is to provide descriptive detailing 
to the HTML for better accessibility and maintenance. In order for the HTML to be easily read and accessed,
I removed all the non-semantic elements such as *div* elements because they do not provide much access
to the different sections a webpage contains. The *div* elements also become a nightmare for maintenance
as they provide no description for its contents. Let's say you need to do maintenance on one of the sections
in the webpage, you will have to search through every *div* before finding the right section.

## Features 

My solution to avoid hours of searching through *div* elements is to provide semantic elements to provide
a description to each section of the webpage. Starting with the header of the webpage I replaced the *div*
element with a more descriptive element, *header*. This element provides the reader with a description
that the section is the header for the webpage. If the reader needed to access the header of the HTML, they
will only have to search for the element *header*, instead of browsing through every *div* element until they
find the heading.

The second element I replaced is inside the header element. The original heading contained a nested *div*
element containing the navigation section of the header. I replaced this nested *div* with a *nav* element
to provide a place the reader can search for to access the navigation section of the heading.

The hero image center of the webpage was lacking in information as a *div* element. I replaced it with a 
*figure* element to provide a little more discription as to what the element contained. 

The informative content section of the webpage is one of the key features as it provides an abundance of 
information so it is crucial to have ease of access to this section to fix any misinformation or any other
error within this section; therefore providing an easier way to locate this section is almost mandatory. I
used the *section* element and nested the 3 *articles* of this webpage. This provided the content section 
ease of access and within it, a location for each article of information within this section.

For the benefits section of this webpage, similarly to the content section, I used the *aside* element nested
with 3 *articles* to provide access to the section right side of the webpage and also access to its contents.

Lastly I used the *footer* element to conclude the webpage.

## Credits

[Jerry Leong](https://www.github.com/jleong20/ "Jerry's Github")

## Technologies

+ **HTML**
+ **CSS**
+ ~~JavaScript~~

## License

MIT License

Copyright (c) 2020 Jerry Leong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

