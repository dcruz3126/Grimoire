---
type: recipe
category:
cuisine:
diet:
status:
rating:
servings:
prep_time:
cook_time:
difficulty:
ingredients:
  - 
added: "{{date}} {{time}}"
---
###### Status
```meta-bind
INPUT[select(
  option(Saved),
  option(Developing),
  option(Testing),
  option(Complete),
  option(Favorite),
  option(Abandoned)
):status]
```
###### Diet
```meta-bind
INPUT[select(
  option(Vegan),
  option(Mini)
):diet]
```

Cuisine
```meta-bind
INPUT[select(
  option(Puerto Rican),
  option(Mexican),
  option(Indian/Thai),
  option(Chinese),
  option(Italian)
):cuisine]
```
Meal
```meta-bind
INPUT[select(
  option(Breakfast),
  option(Main Dish),
  option(Side Dish),
  option(Ingredient),
  option(Dessert),
  option(Baking)
):category]
```

Difficulty
```meta-bind
INPUT[select(
  option(Easy),
  option(Medium),
  option(Hard)
):diet]
```


## Ingredients

- 

## Instructions

1. 

## Sources

1. 
## Development Notes

#### Version 1 

**Changes:**

**Result:**

## Notes

Added {{date}} {{time}}