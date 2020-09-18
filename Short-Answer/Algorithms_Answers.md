#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) - O(n) - The size of "a" grows with the size on "n". There is only one step to this soltution. (or maybe 0(1) cause its constant time and only performs one operation)

b) - O(nlogn) - because there is a loop and a nested loop going through "n"

c) - O(n) - This function is reccursively looping through the length of "n", it is called based on the number of elements. Making this a recursive function.

## Exercise II

    == == ==
    We have to find "f" because we dont know what it is yet. We can just drop one egg at a time until it breaks. That will mean we have hit "f"


    for n in building:
        if egg != broken:
            drop_egg()
        else:
            n = f
            break

    O(n)

We can optimize it by moving 2 floors up each pass instead of 1, reducing the number of eggs dropped by half.

    while x < building.length():
        if egg != broken:
            drop_egg()
            x += 2
        else:
            n = f
            break

    O(log n)
    == == ==
