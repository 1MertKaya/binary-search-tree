# Binary Search Tree Project - www.patika.dev
Our array: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
Let us choose 6 as root.

### Step 1: 
    6
     
        7

         
### Step 2: 
          6
      /       \
    5           7

### Step 3:
                  6
              /       \
          5              7
       /
    1

### Step 4: 
                    6
                /       \
            5               7
        /                       \
    1                               8

### Step 5:
                      6
                  /       \
              5               7
          /                       \
      1                               8
          \
              3
        
### Step 6:
We have chosen 6 a our root so skip "6".

### Step 7:
                      6
                  /       \
              5               7
          /                       \
      1                               8
          \                               \
              3                               9
        
### Step 8:
                      6
                  /       \
              5               7
          /                       \
      1                               8
          \                               \
              3                               9
                  \
                      4
    
### Step 9:
                      6
                  /       \
              5               7
          /                       \
      1                               8
          \                               \
              3                               9
          /       \
      2              4
