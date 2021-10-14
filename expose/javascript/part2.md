1. 3 will be printed var is function scope. input length is 3, i is incremented every loop. when for loop ends, i is 3. so 3 is printed.
2. 150 will be printed. discountPrice is a var. it can be used anywhere in the function. at the last for loop, discountPrice is 150. so after the forloop discountPrice = 150
3. 150 will be printed, finalPrice is a var. it can be used anywhere in the function. finalPrice is updated in every loop, the latest value is 150.
4. [50,100,150] will be returned. for each forloop, a discounted price is calculated and appended to discounted array. in this case discount is 0.5. so we return half the input.
5. it will return error. let is block scope, i can only be reachable within the forloop. it's not defined outside.
6. it will return error. let is block scope, discountedPrice can only be reachable within the forloop. it's not defined outside.
7. it will return 150 since it's defined before the for loop. in the same block as the console.log. it's updated every for loop. so it returns the value in last for loop which is 150.
8. [50,100,150] will be returned. for each forloop, a discounted price is calculated and appended to discounted array. in this case discount is 0.5. so we return half the input.
9. error. let is block scope, not reachable outside
10. 3 will be printed. since length = prices.length
11. [50,100,150] will be returned. for each forloop, a discounted price is calculated and appended to discounted array. since discount is 0.5, we return half the input.
12. 
   1.   student['name']
   2.   student['Grad Year']
   3.   student.greeting()
   4.   student['Favorite Teacher']['name']
   5.   student['courseLoad'][0]
13. 
    1.  '32' : integers map to string. so it's just string concatination
    2.  1 : 3 is converted to integer, 3-2 = 1
    3.  3 : null is mapped to 0
    4.  '3null' : string concatination
    5.  4 : true is mapped to 1
    6.  0 : both false and null are mapped to 0
    7.  '3undefined' : string concatination
    8.  NaN : trying to subtract underfined doesn't work
14. 
    1.  true : '2' is converted to 2
    2.  false : '2' > '1'
    3.  true : '2' become 2
    4.  false : type are different
    5.  false : true is mapped to 1
    6.  true : Boolean(2) is true
15. == don't compare types while === does
16. coding question
17. [2,4,6] : doSomething multiple a number by 2 . modify array execute callback function on every element of input array. since callback is doSomething, we multiple everything by 2.
18. coding question
19. 1 4 3 2 

