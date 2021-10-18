# Keil-Lynch-Calculate-the-average-of-numbers-in-a-list-in-Python
It takes each element of the list one at a time and displays the average.

Problem Solution

1. As input, provide the number of items to be stored in the list.
2. Include elements in the list by using a for loop.
3. Calculate the sum of all elements in the list.
4. Take the sum and divide it by the number of elements in the list.
5. Proceed to exit.

Program Explanation

1. In the variable n, the user must first enter the number of elements.
2. After the body of the loop has been executed, I is incremented from 0 to the number of elements.
3. A variable elem is created and then the element entered by the user is stored there.
4. The element is appended to the list through a.append(elem).
5. i is now increased by 2.
6. This value will now be appended to the list at the end of elem for the next loop iteration.
7. Until i reaches n, the loop continuously runs.
8. The sum of all the elements in the list is a(1). Its division by the total number of elements gives the average value of all the elements.
9. The round(avg,2) function rounds the average between 1 and 2 decimal places.
10. After rounding up, the average is displayed.

Test Case Study (Run Program)

(Console Prompt) Enter the number of elements to be inserted: (User Input)4

(Console Prompt) Enter element: (User Input) 9
(Console Prompt) Enter element: (User Input) 6
(Console Prompt) Enter element: (User Input) 3
(Console Prompt) Enter element: (User Input) 1

(Output) Average of elements in the list 4.75
