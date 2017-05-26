# ps1_3

### Example problem with four adjacent digits
* Store string into a vector of ints
* Adjacent definition
	* digits must be next to each other
* Start at i = 0
* i times i + 1
	* Store result
* result times i + 2
	* += result
* result times i + 3
	* += result
* then store i, i + 1, i + 2, and i + 3 as a string into a map in the key
* store result as an integer into a map as value
* Goto i = 1 and repeat above

* Any 13 digit number with a 0 in it is automatically 0

* If the reslut is less than the previous result then do nothing
* if the result is greater than the previos result then replace the previous result
* print result

