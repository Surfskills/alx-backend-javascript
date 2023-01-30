# 0x02. ES6 classes
***

    __Resources__
    Array
    Typed Array
    Set Data Structure
    Map Data Structure
    WeakMap


    __Learning Objectives__

    At the end of this project, be able to explain to anyone, without the help of Google:

    How to use map, filter and reduce on arrays
    Typed arrays
    The Set, Map, and Weak link data structures

**
	0-get_list_students.js

A function named getListStudents that returns an array of objects.

Each object have three attributes: id (Number), firstName (String), and location (String).

The array contains the following students in order:

    Guillaume, id: 1, in San Francisco
    James, id: 2, in Columbia
    Serena, id: 5, in San Francisco



    1-get_list_student_ids.js

A function getListStudentIds that returns an array of ids from a list of object.

This function is taking one argument which is an array of objects - and this array is the same format as getListStudents from the previous task.

If the argument is not an array, the function is returning an empty array.


   2-get_students_by_loc.js

A function getStudentsByLocation that returns an array of objects who are located in a specific city.

It accepts a list of students (from getListStudents) and a city (string) as parameters.

   3-get_ids_sum.js

A function getStudentIdsSum that returns the sum of all the student ids.

It accepts a list of students (from getListStudents) as a parameter.


   4-update_grade_by_city.js

A function updateStudentGradeByCity that returns an array of students for a specific city with their new grade

It accepts a list of students (from getListStudents), a city (String), and newGrades (Array of “grade” objects) as parameters.

If a student doesn’t have grade in newGrades, the final grade is  N/A.

   5-typed_arrays.js

A function named createInt8TypedArray that returns a new ArrayBuffer with an Int8 value at a specific position.

It accepts three arguments: length (Number), position (Number), and value (Number).

If adding the value is not possible the error Position outside range should be thrown.

   6-set.js

A function named setFromArray that returns a Set from an array.

  7-has_array_values.js

A function named hasValuesFromArray that returns a boolean if all the elements in the array exist within the set.

It accepts two arguments: a set (Set) and an array (Array).

   8-clean_set.js

A function named cleanSet that returns a string of all the set values that start with a specific string (startString).

It accepts two arguments: a set (Set) and a startString (String).

When a value starts with startString you only append the rest of the string.

     9-groceries_list.js

A function named groceriesList that returns a map of groceries with the following items (name, quantity)

  10-update_uniq_items.js

A function named updateUniqueItems that returns an updated map for all items with initial quantity at 1.

It accepts a map as an argument. The map it accepts for argument is similar to the map you create in the previous task.

   100-weak.js

Export a const instance of WeakMap and name it weakMap.

Export a new function named queryAPI

Track within the weakMap the number of times queryAPI is called for each endpoint.

When the number of queries is >= 5 throw an error with the message Endpoint load is high

