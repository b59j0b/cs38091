java c
Assignment 2 
Note: Please make sure that you always use notations consistent with lecture notes. Different notations will not be accepted. 
Question 1 (12 marks) 
Consider   a   relation      R   (A, B, C, D, E, G, H, I, J)       and    its    FD    set      F   =   {AD   →   B, BD   →   G, BE   →   I,   AE   →   DI,   AI   →   E,   AEI   →   C}.
Regarding the   following questions, please give your answers and brief justifications.
(1) Check if AB    →   G.   (1 mark)
(2) Find all the   candidate keys   for   R.   (2   mark)
(3) Determine the highest normal form   of R with   respect to   F.   (2   marks)
(4) Find a minimal   cover Fm for      F.   (2 marks)
(5) Regarding   F,   does the   decomposition   R1   = {ABCDJ},   R2   =   {BDGI},   R3   =   {BCEH}   of R satisfy the lossless join property?   (2   marks)
(6) Provide a step-by-step lossless   decomposition of R   into   BCNF   normal   form.   (3   marks)
Question 2 (8 marks) Consider   the   schedule   below.   Here,   R(*)   and   W(*)   stand   for   ‘Read’   and   ‘Write’,   respectively. T1, T2 and T3 represent   3   transactions,   and t1, t2, …, t12 represents   different timeslots.
Note:    Each transaction begins at the time slot of its first operation and commits right after its last operation (s代 写Assignment 2Java
代做程序编程语言ame timeslot). 
(1) Is the   schedule   serializable?   If it   is   not   serializable,   draw   a   precedence graph;   otherwise, provide an equivalent serial   schedule.   (2   marks)
(2) Use the   Two-Phase Locking protocol to add appropriate locks/unlocks for   each of   the transactions.   (3 marks)
(3) Based   on   the   locks/unlocks   you   added   in   q(2),   if the   transactions   attempt   to   follow the   schedule   in the table, what will   happen?   Please justify your   answer   using the method learned from the   lecture.   (3   marks)
Question 3 (6 marks) 
Consider the following page request   sequence:
P1,   P2,   P1,   P4,   P3,   P7,   P2,   P1,   P4,   P5,   P8,   P6,   P8,   P2,   P8.   Assume there are   3 buffers in the   buffer   pool.
(1)    Sketch the process of   how blocks are replaced in the Least Recently Used (LRU)   policy, and   calculate the cache hit   rate.   (2   marks)
(2)    Sketch the process of   how blocks are replaced in the Most Recently Used (MRU)   policy, and   calculate the cache hit   rate.   (2   marks)
(3)    Sketch the   process   of how blocks   are   replaced   in the   First   In   First   Out   (FIFO)   policy, and   calculate the cache hit   rate.   (2   marks)




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
