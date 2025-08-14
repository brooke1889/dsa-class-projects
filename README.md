Name: Brooklynn Bassett
Email: BrooklynnBassett@my.unt.edu
Course: CSCE 3110
Instructor: Eric Harcourt
Date: 9/16/2023


                        CSCE 3110  Program #1


        Due date:  Tuesday, September 22, 2023


        Design a class template, OrderedCollection, that stores a
        collection of Comparables in an array, along with the current
        size of the collection.  The term 'ordered collection' here
        means a totally ordered set; the elements need not be stored
        in any particular order.

        Use dynamic memory allocation to create a C-style array, and
        provide an array capacity that is generally larger than the
        array size.  Insertion into a full array must result in
        the array being reallocated with a larger capacity.  Refer
        to the text implementation of class Vector in Figures 3.7
        and 3.8.

        Provide public functions isEmpty, makeEmpty, insert, remove,
        findMin, and findMax.  Function remove should take a Comparable
        as argument and search the array for its presence.  It should
        also return a boolean with value true iff the Comparable was
        found and removed.

        Include a main function that instantiates a collection of
        integers, OrderedCollection<int>, and (in a loop) allows an
        interactive user to execute any of the six member functions
        listed above (or to terminate the program).

        Your program should be implemented in a single file named
        prog1_Name.cpp, where Name is your last name, tested using
        gnu gcc, and submitted via Blackboard.

