n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if i==0 or  i==n-1 or j==0 or j==n-1 :
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 5
* * * * * 
*       * 
*       * 
*       * 
* * * * * 


n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if j==0 or  j==n-1 or i==j or i+j==n-1 :
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 5
*       * 
* *   * * 
*   *   * 
* *   * * 
*       *


n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if i==0 or  i==n-1 or i==j or i+j==n-1 :
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
 '''''''''''output''''''''''''
 enter the size 5
* * * * * 
  *   *   
    *     
  *   *   
* * * * * 


n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if j==0 or  i==n-1 :
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
 '''''''''''output''''''''''''
    enter the size 5
*         
*         
*         
*         
* * * * * 


n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if i==0 or  i==n-1 :
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
   '''''''''''output''''''''''''
    enter the size 5
* * * * * 
          
          
          
* * * * * 


n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if j==0 or  j==n-1 :
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
  '''''''''''output''''''''''''
  enter the size 5
*       * 
*       * 
*       * 
*       * 
*       *

n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if i==0 or  j==i or j==n-1:
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 5
* * * * * 
  *     * 
    *   * 
      * * 
       *


n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if j==0 or  j==i or i==n-1:
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 5
*         
* *       
*   *     
*     *   
* * * * * 


n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if i==0 or i==0 or j==0 or j==0:
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 6
* * * * * * 
*           
*           
*           
*           


n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
        if i==n//2 or j==n//2 :
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 5
    *     
    *     
* * * * * 
    *     
    *     



    n=int(input("enter the size"))
for i in range(n):
    for j in range(n):
            print("*",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 5
* * * * * 
* * * * * 
* * * * * 
* * * * * 
* * * * * 


n=int(input("enter the size"))
for i in range(n):
    for j in range(i):
            print("*",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 5

* 
* * 
* * * 
* * * * 


n=int(input("enter the size"))
for i in range(n):
    for j in range(i):
            print("*",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 10

1 
2 2 
3 3 3 
4 4 4 4 
5 5 5 5 5 
6 6 6 6 6 6 
7 7 7 7 7 7 7 
8 8 8 8 8 8 8 8 
9 9 9 9 9 9 9 9 9 


n=int(input("enter the size"))
for i in range(1, n+1):
    for j in range(n-i):
         print(' ',end=' ')
    for k in range(2*i-1):
         print("*",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 9
                * 
              * * * 
            * * * * * 
          * * * * * * * 
        * * * * * * * * * 
      * * * * * * * * * * * 
    * * * * * * * * * * * * * 
  * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * 


n=int(input("enter the size"))
for i in range(n,0,-1):
    for j in range(n-i):
         print(' ',end=' ')
    for k in range(2*i-1):
         print("*",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 9
* * * * * * * * * * * * * * * * * 
  * * * * * * * * * * * * * * * 
    * * * * * * * * * * * * * 
      * * * * * * * * * * * 
        * * * * * * * * * 
          * * * * * * * 
            * * * * * 
              * * * 
                * 


n=int(input("enter the size"))
for i in range(1, n+1):
    for j in range(n-i):
         print(' ',end=' ')
    for k in range(2*i-1):
         print("*",end=' ')
    print()
for i in range(n-1,0,-1):
    for j in range(n-i):
         print(' ',end=' ')
    for k in range(2*i-1):
         print("*",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 9
                * 
              * * * 
            * * * * * 
          * * * * * * * 
        * * * * * * * * * 
      * * * * * * * * * * * 
    * * * * * * * * * * * * * 
  * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * 
  * * * * * * * * * * * * * * * 
    * * * * * * * * * * * * * 
      * * * * * * * * * * * 
        * * * * * * * * * 
          * * * * * * * 
            * * * * * 
              * * * 
                * 



n=int(input("enter the size"))
for i in range(1, n+1):
    for j in range(n-i):
         print(' ',end=' ')
    for k in range(2*i-1):
         print("joshika",end=' ')
    print()
for i in range(n-1,0,-1):
    for j in range(n-i):
         print(' ',end=' ')
    for k in range(2*i-1):
         print("joshika",end=' ')
    print()
'''''''''''output''''''''''''
enter the size 4
      joshika 
    joshika joshika joshika 
  joshika joshika joshika joshika joshika 
joshika joshika joshika joshika joshika joshika joshika 
  joshika joshika joshika joshika joshika 
    joshika joshika joshika 
      joshika 
