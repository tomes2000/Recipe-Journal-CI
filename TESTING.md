## Automated Testing

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS. I have checked the HTML via direct input and also by inspecting the page source and running this through the validator.

* [Recipes Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Frecipe-journal-aavash-7fc97436a7e3.herokuapp.com%2F) - No errors or warnings.
* [Register Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Frecipe-journal-aavash-7fc97436a7e3.herokuapp.com%2Fregister) - No errors or warnings.
* [Login Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Frecipe-journal-aavash-7fc97436a7e3.herokuapp.com%2Flogin) - No errors or warnings.
* [Recipes](https://validator.w3.org/nu/?doc=https%3A%2F%2Frecipe-journal-aavash-7fc97436a7e3.herokuapp.com%2Fget_recipes) - No errors or warnings.
* [Add A Recipe](https://validator.w3.org/nu/?doc=https%3A%2F%2Frecipe-journal-aavash-7fc97436a7e3.herokuapp.com%2Fadd_recipe) - No errors or warnings.
* [Add A Cuisine](https://recipe-journal-aavash-7fc97436a7e3.herokuapp.com/get_cuisines) - No errors or warnings.
* [Profile](https://validator.w3.org/nu/?doc=https%3A%2F%2Frecipe-journal-aavash-7fc97436a7e3.herokuapp.com%2Fprofile%2Fadmin) - No errors or warnings.
* [Edit Cuisine](https://validator.w3.org/nu/?doc=https%3A%2F%2Frecipe-journal-aavash-7fc97436a7e3.herokuapp.com%2Fedit_cuisine%2F64d3c3568e713ddc22e1fe5e) - Minor Warnings that don't affect the funcitonality.
* [Edit Recipe](https://validator.w3.org/nu/?doc=https%3A%2F%2Frecipe-journal-aavash-7fc97436a7e3.herokuapp.com%2Fedit_recipe%2F64d35365e202d0bc73612233) - Minor Warnings that don't affect the funcitonality.

### JavaScript Validator

[jshint](https://jshint.com/) was used to validate the JavaScript.
 * [script.js](documentation/jshint.png)

Comments made are only related to JS version. No errors found.

### Python Validator

I used the [pycodestyle](https://pypi.org/project/pycodestyle/) package within my IDE to ensure that my code meets PEP8 guidelines.

Minor errors that were fixed related to spacing between code.

[flask_app.py](documentation/pythontest.png)

### WAVE Testing

[WAVE](http://wave.webaim.org/) (Web Accessibility Evaluation Tool) allows developers to create content that is more accessible to users with disabilities. It does this by identifying accessibility and WGAC errors.

I have used the WAVE testing tool to try and ensure there are no accessibility issues with my site.

### Lighthouse - Desktop Results

[Get Recipes](documentation/get_recipes.png)
[Add Recipe](documentation/add_recipe.png)
[Edit Recipe](documentation/edit_recipe.png)
[Profile](documentation/get_recipes.png)
[Get Cuisines](documentation/get_cuisines.png)
[Add Cuisines](documentation/add_cuisine.png)
[Edit Cuisines](documentation/edit_cuisine.png)
[Login](documentation/login.png)
[Register](documentation/register.png)
