# Exercise: Postman
Use [Postman](https://www.postman.com/) to call the following APIs:
* [Free Cocktail Db](https://www.thecocktaildb.com/api.php):
	* `GET`: search a cocktail by name (e.g. `s=margarita`)
	* `GET` search ingredients by name (e.g. `i=rum`)
* [Dummy REST API Example](http://dummy.restapiexample.com/)
	* `GET`: get info about the employee with `id=14`
	* `POST`: create a new record sending the following JSON: `{"name":"John", "salary": "40000", "age":"35"}`
* [Agify.io](https://agify.io/):
	* `GET`: send an *array of names* to predict the age for multiple names: `lucy`, `bob` and `alice`