# Recipe App

This JS app will traverse the DOM on a given page and look for recipe data in one of the following formats:

* http://microformats.org/wiki/hrecipe
* http://schema.org/Recipe
* http://www.data-vocabulary.org/Recipe/

It will then parse the recipe data on the page, and create a uniform Recipe object that includes the data and reference to DOM elements containing the related content.
