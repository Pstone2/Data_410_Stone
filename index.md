## **Hello World Data 410**

**Patrick Stone**

**Edited: 2/4/2022**

**Spring 2022**

![](https://th.bing.com/th/id/R.b8f4c0b889c4a89a02a0c93d4be13d33?rik=bine2TbYbOjrrw&riu=http%3a%2f%2f2.bp.blogspot.com%2f-cpmtMHI-d4Y%2fTzErKJCaKnI%2fAAAAAAAA27I%2f6ZHcXekCynU%2fs1600%2fDungeonsDragons0cover.jpg&ehk=2nCZOKKWbbZCS7UYvGKkoNXta2B9FUlkjep%2bz%2fq%2fyrc%3d&risl=&pid=ImgRaw&r=0 "Dragon")

## **About me**

My name is Patrick Stone.
I am a sophomore data science major.
I am excited to learn about Machine learning.
In my free time, I mainly enjoy playing Dungeons & Dragons and Magic the Gathering.
I hope to graduate and specialize in machine learning. 

## **Math**

**Basic addition**

1 + 10 = 11

## **Python Code**

```python
#import the the library we need
from mpmath import mp

#define the function
def pi_digets(x):
  mp.dps = x+1 #make it so that it will give you the number of decimal places you imput
  if str(x).isnumeric() == True: #check to see if you made a valid imput 
    return print(mp.pi) #print the correct value
  else:#if invalid 
    return print('You did not imput an int for x')
```
