# List of Vue

Create a vuejs app that displays a list of items and allow user to add new items. You
get to choose your own domain topic, however take a look at requirements to help
guide your choice.

## Components

Basic component structure (use real domain names):

```
App
 |
 +- AddItemForm
 |
 +- ItemList
       |
       +- Item
```

## Items

Pick a domain topic of interest. Limited requirements:

* Has at least three properties
* Conditional rendering based on one of the properties (`v-if`)

## Functionality

1. Create dummy data with at least 3-4 items and return as `data` of `App`
1. Pass callback function to add form, and call when submitted
1. BONUS: Pass callback function thru list and to item to remove when button clicked

## Rubric

* List of Items (List and Item component) **3pts**
* Add Form **2pts**
* Update functionality works (coordination of data in App) **2pts**
* Conditional rendering (`v-if`) **1pt**
* Clean and Idiomatic Project Organization, JavaScript and VueJS **2pts**
