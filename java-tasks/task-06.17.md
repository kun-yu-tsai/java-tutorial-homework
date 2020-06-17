# Class

## Tip:

You can format the code with below command:
`Cmd + Option + L`

## Create the root class

1. Create a new class in your project. Maybe name it with `ClassPractice`
2. Create a `main function` in the class.
3. Create below classes in the `ClassPractice` class.
4. While you're creating below classes, remember to put it as below format

```java
class ClassPractice{
	public static void main(String[] args) {

	}
	
	// remember to put static here.
	static class NameOfTheClass{ 

	}
}
```

## Country class

### Define a class named Country with below attribute

```jsx
name  // String
population // int
areaSqKm  // int
totalGDP  // int
```

Create class instances at least 5 countries. Try to cover countries Taiwan, Eswatini, Heidi.

### Add methods (function) in the Country class.

1. `int gdpPerCaptital()`
GDP / population. Do the calculation in function and return it.
2. `int areaSqMi()`
the area in square miles. Same as above

Try to print them see if they're working as expected.

### Method to get string information

1. `String briefInfo()`
create a string like below

    Country Taiwan has XXX population with a total area of XXX square km. Total GDP is XXX, per capital is XXX.

    and return it.

2. `showBriefInfo()`
in this method, print out the info we get in the previous method. Doing this by directly calling the previous function!

## Hero class

### Write a class named Hero with below attributes and methods

```jsx
name; // String
weapon; // String
actionPoint; // Integer
hp; // Integer
mp; // Integer
```

### Write methods for this class

```jsx
attack() // decrease actionPoint by 5

fireball() // decrease mp by 10

heal(int healHp) // increase hp by healHp

beingAttack(int decreasedHp) // decrease hp by decreasedHp
```

### Write a method to print all information in String

```jsx
showAllInfo()
```

Do something like what we did in the Country class
