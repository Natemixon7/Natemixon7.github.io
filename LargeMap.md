[Back to Portfolio](./)

Large Map
===============

-   **Class:** CSCI 315
-   **Grade:** B+
-   **Language(s):** C++
-   **Source Code Repository:** [Natemixon7/Map](https://github.com/Natemixon7/Map)  
    (Please [email me](mailto:NRMixon@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This program assigns a unique nonnegative 32-bit integer to each student's first and last name. To optimize search and removal operations, the data is stored in a sorted vector, with names being inserted in sorted order. A binary search algorithm is utilized to efficiently locate keys for adding or removing entries. A standout feature of this program is the howMany() function, which enables quick retrieval of the count of names matching a user-specified criterion. For instance, if a user searches for names starting with "Jo," the function would return 3 if the dataset includes "John," "Jonah," and "Jonathan."

## How to compile and run the program

```bash
Need separate .txt files for first names and last names
make
./map-test
```

## UI Design

This program has no UI but there are lots of tests written in the test folder.

![screenshot](images/MapImages/Example.png)  
Fig 1. Compilation example

## 3. Additional Considerations

This project was graded based strictly on performance and did not require a UI. For a best understanding of the program look through the commented code and test cases. This program utilizes binary search and therefore the time complexity of the remove and get functions are O(log(n)).

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
