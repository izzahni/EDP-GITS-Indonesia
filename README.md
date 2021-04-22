## EDP-GITS-Indonesia

### QUESTION 1
Given a binary array, find the maximum number of consecutive 1s in this array.

#### Example :
    Input: [1,1,0,1,1,1]
    Output: 3
    Explanation: The first two digits or the last three digits are consecutive 1s. The maximum number of consecutive 1s is 3.

    Input: [1,0,0,1,0,1,1]
    Output: 2
    Explanation: The first two digits or the last three digits are consecutive 1s. The maximum number of consecutive 1s is 2.

#### Note :
1. The input array will only contain 0 and 1
2. The length of input array is a positive integer and will not exceed 10.000

### QUESTION 2
Write a function that reverses a string using a recursive function. Input of function using char[] or array of character

#### Example :
    Input: ["h","e","l","l","o"]
    Output: ["o","l","l","e","h"]

#### Note :
1. You can’t using default function reserve
2. You can’t using looping for reserve function
3. Only can use recursive for solved

### QUESTION 3
Write function to find Balanced Brackets. Bracket is considered to be any one of the following characters: ( , ) , { , } , [ , or ]. Check brackets matched pairs between opening bracket and close bracket with return string YES or NO.

#### Example :
    Input: { [ ( ) ] }
    Output: YES
    Explanation: every bracket it’s balance, between opening bracket and close bracket:
    opening : { it’s balance with }
    opening : [ it’s balance with ]
    opening : ( it’s balance with }
    
    Input: { [ ( ] ) }
    Output: NO
    Explanation: The string { [ ( ] ) } is not balanced because the brackets enclosed by the matched pair { and } are not balanced: [ ( ] ).
    
    Input: { ( ( [ ] ) [ ] ) [ ] }
    Output: YES
    Explanation: every bracket it’s balance, between opening bracket and close bracket, although the structure of bracket irregular
