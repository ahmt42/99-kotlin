# K-99: Ninety-Nine Kotlin Problems

This collection of problems aims to provide you with a platform to hone your logic programming abilities. Your primary objective should be to unearth the most refined solution for each problem. While efficiency holds merit, prioritizing logical clarity is paramount. There might be built-in predicates that offer seemingly effortless solutions to some of the (easier) problems. However, by attempting to devise your own solutions, you will gain a deeper understanding.

That's a good explanation of the difficulty levels in problems.

Here's a breakdown of the typical difficulty associated with each asterisk notation:
Single asterisk *: Easy problems, solvable within 15 minutes or so. 
Double asterisk **: Intermediate difficulty problems, taking a skilled programmer 30-90 minutes to solve. 
Triple asterisk ***: Difficult problems that may require several hours or more to find a good solution. 
These are just general guidelines, and the actual difficulty can vary depending on your experience and the specific problem.

### Difficulty Levels in Prolog Problems

Prolog problems often use asterisks (*) to denote their difficulty level. Here's a breakdown of what each notation typically indicates:

* Single asterisk (*) : Easy problems. These can be solved by beginners within 15 minutes or so.
* Double asterisk (**) : Intermediate difficulty problems. Solving these might take a skilled Prolog programmer 30-90 minutes.
* Triple asterisk (***) : Difficult problems.  Finding a good solution for these can take several hours or even more.

**Note:** These are just general guidelines. The actual difficulty can vary depending on your experience and the specific problem you're tackling.

## Lists

### [P01][] (*) Find the last element of a list.
Example:
``` kotlin
> last(listOf(1, 1, 2, 3, 5, 8))
8
```

### [P02][] (*) Find the last but one element of a list.
Example:
``` kotlin
> penultimate(listOf(1, 1, 2, 3, 5, 8))
5
```

### [P03][] (*) Find the Nth element of a list.
By convention, the first element in the list is element ``0``.
Example:
``` kotlin
> nth(2, listOf(1, 1, 2, 3, 5, 8))
2
```

### [P04][] (*) Find the number of elements of a list.
Example:
``` kotlin
> length(listOf(1, 1, 2, 3, 5, 8))
6
```

### [P05][] (*) Reverse a list.
Example:
``` kotlin
> reverse(listOf(1, 1, 2, 3, 5, 8))
[8, 5, 3, 2, 1, 1]
```



[P01]: https://github.com/ahmt42/99-kotlin
[P02]: https://github.com/ahmt42/99-kotlin
[P03]: https://github.com/ahmt42/99-kotlin
[P04]: https://github.com/ahmt42/99-kotlin
[P05]: https://github.com/ahmt42/99-kotlin


