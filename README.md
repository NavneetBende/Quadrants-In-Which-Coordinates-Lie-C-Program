# Quadrants-In-Which-Coordinates-Lie-C-Program

Quadrants in which coordinate lies in C
Here, we will discuss the program for Quadrants In Which Coordinates Lie in C. The C program reads the coordinate point in a x-y coordinate system and identify the quadrant. The program takes X and Y. On the basis of x and y value, the program will identify on which quadrant the point lies.

Quadrant in which coordinates lie in C
While loop in C
Working :
According mathematics quadrants rules:

X  is positive integer as well as Y is also positive a integer it signifies first quadrant.
X  is negative integer but Y is positive integer it signifies second quadrant.
X  is negative integer as well as Y is also negative integer it signifies third quadrant.
X  is positive integer but Y is negative integer it signifies fourth quadrant.
Algorithm :
Get value of x & y
If ( x>0 and y>0 ) First Quadrant
If ( x<0 and y>0 ) Second Quadrant
If ( x<0 and y<0 ) Third Quadrant
If ( x>0 and y>0 ) Fourth Quadrant
If ( x=0 and y=0 ) Origin
If ( x!=0 and y=0 ) x-axis
If ( x>0 and y>0 ) y-axis
Quadrants in which coordinates lies
C code
Run
#include<stdio.h>

int main()
{
	
    //for initialization of coordinates
    int x, y; //user input
    printf("Insert the value for variable X and Y : ");
    scanf("%d %d", &x, &y);
    
    //find true condition of first quadrant 
    if (x > 0 && y > 0)
        printf("point (%d, %d) lies in the First quadrant\n",x,y);
    
    //find second quadrant
    else if (x < 0 && y > 0)
        printf("point (%d, %d) lies in the Second quadrant\n",x,y);
    
    //To find third quadrant
    else if (x < 0 && y < 0) printf("point (%d, %d) lies in the Third quadrant\n",x,y); //To find Fourth quadrant else if (x > 0 && y < 0)
       printf("point (%d, %d) lies in the Fourth quandrant\n",x,y);
    
    //To find dose not lie on origin
    else if (x == 0 && y == 0)
        printf("point (%d, %d) lies at the origin\n",x,y);
    
    //On x-axis
    else if (y==0 && x!=0)
        printf("point (%d, %d) on x-axix\n",x,y);
    
    //On y-axis
    else if (x==0 && y!=0)
        printf("point (%d, %d) on at y-axix\n",x,y);
    

return 0;
}
Output
Insert the value for variable X and Y : -3 -33
point (-3, -33) lies in the Third quadrant
Related Pages
Decimal to Binary conversion

Decimal to Octal Conversion

Decimal to Hexadecimal Conversion

Permutations in which n people can occupy r seats in a classroom 

Octal to Binary conversion

Quadrants in which a given coordinate lies

Prime Course Trailer

Related Banners
Get PrepInsta Prime & get Access to all 200+ courses offered by PrepInsta in One Subscription

Get Prime
