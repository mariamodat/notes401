# Intetn filters
## Allowing Other Apps to Start Your Activity
what does that mean ?
when another activities want to share their content , your activity will be one of the available options. how so ?
we  need to add an < intent-filter> element in our manifest file for the corresponding < activity> element.

## Add an Intent Filter
In order to properly define which intents your activity can handle, each intent filter you add should be as specific as possible in terms of the type of action and data the activity accepts.
so we can declare multiple intents so each intent filter specifies the type of intents it accepts based on the intent's action, data, and category.

![img](https://tutorial.eyehunts.com//wp-content/uploads/2018/06/what-is-android-Intent-Filters-examples.png)

### Action
ACTION_VIEW as a string
we will Specify this in the intent filter with the < action> element.

### Data
A description of the data associated with the intent

### Category
Adds a category name to an intent filter.
Standard categories are defined in the Intent class as CATEGORY_name constants.