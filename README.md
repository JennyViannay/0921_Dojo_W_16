# 0921_Dojo_W_16

# Group Strings by Length

## Description
Write a function groupByLength that **takes an array of strings** and **returns an array of arrays (of strings)**. The sub arrays contain only strings of the same length. The sub arrays are ordered in encresing length.

Example:
```javascript
groupByLength(['wild', 'code', 'school'])
// returns:
[['wild', 'code'],['school']]

groupByLength(['aaa', 'aa', 'a', 'bb'])
// returns:
[['a'],['aa', 'bb'], ['aaa']]
```


## Requirements
- Pass all the tests
- To run the tests: `npm test`

----------------------------------------------------------------------------------------------------------------------------------------------------------------

# Too Far:

## Description
Given a distance in KM, a time in minutes and an assumed walking speed of 1km/hour, calculate if a person can cover the distance in the given time.

Return true of false.

### Tips:

Normalise data at the earliest opportunity. Use unixtime!

Optional: Improve your code to support returning a third state, whereby the person can cover the distance if they run. Assume a running speed of 2km/hour.

Output should look like this:

2.5km and 40 minutes, the code should return false. 0.5km and 40 minutes, the code should return true.

## Bonus
- Write some test in new file for tooFar function and test your code (don't hesitate to inspire you from the test.js file)
