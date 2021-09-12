# lists_and_ranges_pylab

<img src="https://i.imgur.com/DPzk4Ok.png">

# Python Containers and Ranges - Lab


## Exercises

#### Exercise 1

- Create a list named `students` containing some student names (strings).
- Print out the second student's name.
- Print out the last student's name. (how would you do this if you didn't know the length of the students list?)

#### Exercise 2

- Create a tuple named `foods` containing the same number of foods (strings) as there are names in the `students` list.
- Use a `for` loop to print out the string "{food goes here} is a good food"

#### Exercise 3

- Using a `for` loop, print just the last two food strings from `foods`.

#### Exercise 4

- Create a dictionary named `home_town` containing the keys of `city`, `state` and `population`.
- Print a string with this format:<br>"I was born in _city_, _state_ - population of _population_"

#### Exercise 5

- Iterate over the _key: value_ pairs in `home_town` and print a string for each item, for example:<br>"city = Arcadia"<br>"state = California"<br>"population = 58000"

#### Exercise 6
- Create a list named `current_students` and fill it with a few student strings.
- Create an empty list named `cohort`.
- Using a `for` loop, add one dictionary to the `cohort` list for each student name. Each dictionary should have this shape:

	```python
	{
		'student': 'Tina',
		'currently_enrolled': True
	}
	```

- Test out your handy-word by printing `cohort`.
- Loop over `cohort` printing out a message for each student dictionary in the list.
```bash
Jane is currently enrolled
Stu is currently enrolled
Derek is currently enrolled
```

## Hungry for More - List Comprehensions

#### Exercise 7

- Using the list of `students` and list comprehension, assign to a variable named `awesome_students` a new list containing strings similar to this:<br>["Tina is awesome!", "Fred is awesome!", "Wilma is awesome!"]
- Iterate over `awesome_students` printing out each string.

#### Exercise 8

- Using the tuple `foods` and list comprehension create a new list only including the foods that contain the letter 'a'.












