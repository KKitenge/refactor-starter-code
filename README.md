# Code Refactoring - Module 1 Mar 23


## Description

This project gives access to users who can look at the provided website HTML and confirm if it is clean,
or if it is in need of correction. If editing is needed, the aim is to gain knowledge with HMTL, CSS and 
the workflow associated with Visual Code and command line interaction.

[Live Site Link]( )

## Code Snippet Example

### Original HTML code:

    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>

and

    <div class="content">
        <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            

### Corrected Code

The website's title was changed from website to Horiseon.

    <meta charset="UTF-8">
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Horiseon</title>


The change was made from div to id so that Search Engine Optimization would be linked correctly as an anchor, and navigate to the correct position on the page. Image information was added for accesibility.

    <section class="content">
        <div id="search-engine-optimization" class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="notebook with laptop and pencils">
            <h2>Search Engine Optimization</h2>  


## Installation

* Create a repository with a preferred name.
* Clone the current code found here.
* Look it over and make any necessary changes.


## Credit

[W3Schools.com](https://www.w3schools.com)
[MDM Web Doc](https://developer.mozilla.org/en-US)
[Visual Studio Code](https://code.visualstudio.com)
[GitHub](https://github.com)

## License

Copyright (c) Horiseon