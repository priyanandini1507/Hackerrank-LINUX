# Question:
Your task is to use for loops to display only odd natural numbers from  1 to 99.

## Input Format:

There is no input.

## Output Format:

1
3
5
.
.
.
.
.
99  

## Sample Input:

-

## Sample Output:

1
3
5
.
.
.
.
.
99  

## LINUX code:
### Method 1:
```Linux
for i in {1..99..2}
do
echo $i 
done
```

### Method 2:
```Linux
i=1
while [ $i -lt 100 ]
do
echo $i
i=$(($i+2))
done
```

### Method 3:
```Linux
for i in {1..100}
do 
num=$i%2;
if [[ num -ne 0 ]];
then
echo $i
fi
done
```

## Output:
1
3
5
7
9
11
13
15
17
19
21
23
25
27
29
31
33
35
37
39
41
43
45
47
49
51
53
55
57
59
61
63
65
67
69
71
73
75
77
79
81
83
85
87
89
91
93
95
97
99
