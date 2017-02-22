# Problem
In a wedding reception, guests were seated around a circular table for six. Before the dinner, the newlyweds asked each guest to shake hands (once) with everyone on the table. How many handshakes were made in each table?

# Suggeseted Solutions

## Solution 1: 
We represent the 6 visitors in each table by letters A, B, C, D, E and F.  We use the tree diagram as shown in the first figure to represent handshakes. Person A handshakes with each person at the table: persons B, C, D, E, and F. These handshakes are represented by segments. Person B handshakes with persons A, C, D, E, and F. But a handshake between person A and B is the same as the handshake of B and A (see red letters). Therefore, each handshake was counted twice.
 ![tree of handshakes](.guides/img/image001.png)
The figure above shows that there are 30 handshakes in a table, but since we have counted the handshakes twice, we divide the total number of handshakes by 2. This gives us 15 handshakes.


## Solution 2: 
We use a table to exhaust the number of handshakes.  Each person does not have to handshake with himself, so we put the black diagonal. We represent the handshake by naming the person in the column first, and then the row as shown in the third figure.  So column B and row A is handshake BA. We now construct all the possible handshakes.
 
![grid of handshakes](.guides/img/image002.png)
Notice that the handshakes in the yellow part of the table are repeated in the gray part with the order of the representation reversed; that is, FE in the yellow cell, and EF is the gray cell. Since handshake EF is the same as handshake FE, to determine the number of handshakes, we just count the yellow-colored cell (or the handshakes in the gray-colored cells). By counting the cells, we see that there are only 15 handshakes.

## Solution 3: 
A geometric representation may also be used to solve the problem. The handshake problem is equivalent to finding the number of segments that connect six non-collinear points.
 ![geometric of handshakes](.guides/img/image003.png)
In this solution, it is easy to count the segments, which is equivalent to the handshakes.   It is clear that there are 15 handshakes.

## Solution 4: 
There are six persons in a table, each of whom, will handshake the other five. Therefore, there are 30 handshakes. However, the handshake of person A and person B is the same as the handshake of person B and person A. Therefore, we have counted the handshakes twice.  Hence, there are only 15 handshakes that happened.

