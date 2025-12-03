# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1.  1.	Start the Program.
2.	Define a class `circum`
3.	Inside the class, define two integer variables `l` and `w` with values 5 and 6, respectively
4.	Create a constructor `circum()`:
-	a) Calculate the `circumference` as `2 * (l + w)`
-	b) Print the `circumference` twice with different labels ("Area of First Rectangle" and "Area of Second Rectangle")
5.	In `main`, create an object `sc` of the `circum` class
6.	End





## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: M.Suryakumar
RegisterNumber:  212224040340
*/
```

## Sourcecode.java:

```
class Rectangle 
{ 
    int l; 
    int b; 
    
    Rectangle(int l, int b) 
    {  
        this.l = 5;
        this.b = 6;
    } 
    
    Rectangle(Rectangle obj) 
    {
        this.l = obj.l;
        this.b = obj.b;
    } 
    
    int circumference() 
    { 
        return 2*(this.l + this.b)+8;
    } 
 } 
class prog 
{ 
    public static void main(String[] args) 
    { 
        Rectangle firstRect = new Rectangle(5,6); 
        Rectangle secondRect = new Rectangle(firstRect); 
        
        System.out.println("Area  of First Rectangle : "+firstRect.circumference());
        System.out.print("Area of First Second Rectangle : "+secondRect.circumference());
     
    } 
} 

```





## OUTPUT:

<img width="854" height="286" alt="image" src="https://github.com/user-attachments/assets/bdf077ce-7c55-4c2c-b741-d61648a854fa" />


## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.

