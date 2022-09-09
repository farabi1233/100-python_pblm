# 6.3 Calculate grades

##  The problem
Calculate grade of five subjects. 

## Hint
So, you have to take five inputs. These will be the marks of five subjects. Then, create the average. 

Once you have the average. It just running an if-else. And decide the grade. 

## The Solution
```python
print('Enter your marks:')
sub1=int(input("First subject: "))
sub2=int(input("Second subject: "))
sub3=int(input("Third subject: "))
sub4=int(input("Fourth subject: "))
sub5=int(input("Fifth subject: "))
 
avg=(sub1+sub2+sub3+sub4+sub5)/5
 
if avg >= 90:
   print("Grade: A")
elif avg >= 80:
   print("Grade: B")
elif avg >= 70:
   print("Grade: C")
elif avg >=60:
   print("Grade: D")
else:
   print("Grade: F")

