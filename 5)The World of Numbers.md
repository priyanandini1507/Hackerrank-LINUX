## Problem statement:

Given two integers, X and Y, find their sum, difference, product, and quotient.

## Input Format

Two lines containing one integer each (X and Y, respectively).

## Output Format

Four lines containing the sum (X+Y), difference (X-Y), product (XxY), and quotient (X/Y), respectively.
(While computing the quotient, print only the integer part.)

## Sample Input

5
2

## Sample Output

7
3
10
2

## Explanation

5 + 2 = 7
5 - 2 = 3
5 * 2 = 10
5 / 2 = 2 (Integer part)

## Program
```Linux
read x
read y

if (($x<-100)) && (($x>100)) || (($y<-100)) && (($y>100))
then
 echo "over range"
 exit 1
else
    #Sum
    echo $(($x+$y))
    #difference
    echo $(($x-$y))
    #product
    echo $(($x*$y))
    #quotient
    echo $(($x/$y))
fi
```
