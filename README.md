# CodePen Clone

##### Clone of CodePen website, September 7, 2018

#### By AJ MCgladdery

#### Screenshots

### Original Site: codepen.io
![Original Site](https://raw.githubusercontent.com/username/projectname/branch/path/to/img.png)

### Cloned Site:
![Cloned Site](https://raw.githubusercontent.com/username/projectname/branch/path/to/img.png)

## Description

This responsive website clones main components of the website CodePen. This project makes use of SASS variables and mixins to DRY up stylesheets.

### BDD specs
* This website displays three cards per row when viewport exceeds 914px.
  * Example Input: viewport width >= 914px
  * Example Output: three cards per row

* This website displays two cards per row when viewport is between 605px and 914px.
  * Example Input: viewport width > 605 && < 914px
  * Example Output: two cards per row

* This website displays one card per row when viewport is less than 605px.
  * Example Input: viewport width < 605px
  * Example Output: one card per overflow

* This website hides header word links when viewport is smaller than 914px.
  * Example Input: viewport width < 914px
  * Example Output: header word links hide

* This website hides bell icon when viewport is smaller than 605px.
  * Example Input: viewport width < 605px
  * Example Output: bell icon hides

## Setup

Install CodePen Clone by cloning this repository.

## Technologies Used

HTML, CSS, JavaScript, SASS, and jQuery

### Legal

Copyright (c) 2018 **AJ Mcgladdery**

This software is licensed under the MIT license.
