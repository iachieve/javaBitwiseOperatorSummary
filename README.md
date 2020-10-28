# java Bitwise Operator Summary

##### Bitwise AND (&):

|   A	|  B 	|  A&B 	|
|---	|---	|---	|
|  1 	|  1 	|  1 	|
|  1 	|  0 	|  0 	|
|  0 	|  1 	|  0 	|
|  0 	|  0 	|  0 	|

##### Bitwise OR (|):

|   A	|  B 	|A OR B |
|---	|---	|---	|
|  1 	|  0 	|   1	|
|  1 	|   1	|   1	|
|  0 	|   1	|   1	|
|  0	|   0	|   0	|


##### Bitwise XOR (^):

|   A	|  B 	|A ^ B |
|---	|---	|---	|
|  1 	|  0 	|   0	|
|  1 	|   1	|   1	|
|  0 	|   1	|   1	|
|  0	|   0	|   0	|

##### Bitwise NOT (~):

| A  | ~A  |
|---|---|
|  1 | 0  |
|  0 | 1  |

```java
// two's complement
// ~(X)==(-X)-1
System.out.println(~10) == -11;
// -(10)-1 = -11
```


