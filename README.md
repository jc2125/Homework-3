# Homework-3

Number 1:

*FOR NUMBER ONE BE SURE TO LOOK AT ATTACHED IMAGE WHEN LOOKING AT THE README FILE IN ORDER TO SEE VISUALLY MY EXAMPLE TREE*

I will include the function algorithms in one file (Number 1 Grade File), then a main file in uploaded as a seperate file so that the main file can be ran and tested (Number 1 Test File). The first file will be in order for you guys to analyze the algorithms of the functions required.

Note: Lets say you choose the program to have three children per parent, the format of my heapArray would look like:
    [root, parent 1, child 1 of parent 1, child 2 of parent 1, child 3 of parent 1, parent 2, child 1 of parent 2 ....]
      So for example in array {77,14,10,8,50,7,838,7001,323,9} with 10 elements and 3 children per parent:
        How Tree Would Look: 
                                              (0) 77 = root
       (1) 14 = parent 1 (child 1 of root)    (2) 10 = parent 2 (child 2 of root)    (3) 8 = parent 3 (child 3 of root)
       (4) 50 = child 1 of parent 1           (7) 7001 = child 1 of parent 2                     [no children]
       (5) 7 = child 2 of parent 1            (8) 323 = child 2 of parnet 2
       (6) 838 = child 3 of parent 1          (9) 9 = child 3 of parnet 2
        
        heapArray = [77,14,50,7,838,10,7001,323,9,8] <- i formatted the heapArray this way in order to visualize the tree easier for me with arrays through my prograM
