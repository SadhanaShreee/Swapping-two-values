# Swapping of two variables
## AIM:
To write a python program for swapping of two values
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the two values from the user
### Step 2: 
Assign the value of second variable to a temporary variable 
### Step 3: 
Assign the value of the first variable to the second variable.
### Step 4:  
Assign the value in temporary variable to the first variable
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## PROGRAM:
                    def swap(a,b):
                        t=a
                        a=b
                        b=t
                        return a,b
                    a=input()
                    b=input()
                    a,b=swap(a,b)
                    print('Swapped values are: {} {}'.format(a,b))


## OUTPUT:
![Screenshot 2024-03-21 134412](https://github.com/SadhanaShreee/Swapping-two-values/assets/144517664/6fb67c23-a43a-4d98-98c3-9dd67d67894f)


## RESULT:
Thus the swapping of two values are successfully executed



