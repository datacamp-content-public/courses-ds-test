---
title: Test
description: 'This is a test.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

This is an example exercise.

`@instructions`
Print to screen "Hi, my name is DataCamp.

`@hint`
Lookup the built-in function `print`.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# your solution here:

```

`@solution`
```{python}
print('hi, my name is DataCamp')
```

`@sct`
```{python}
Ex().has_output(r'[H|h]i,\s+my name is \w+')
```

---

## Multiple choice test

```yaml
type: PureMultipleChoiceExercise
key: f65d341d52
xp: 50
```

Mark answer 1.

`@hint`
Answer 1.

`@possible_answers`
1. [1]
2. 2
3. 3
4. 4

`@feedback`
1. Correct
2. 2 is wrong
3. 3 is wrong
4. 4 is wrong
