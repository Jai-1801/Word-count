# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open the file in read mode
### Step 2: 
iterate using for loop
 
### Step 3: 
increment the word with length of the word

### Step 4:  
assign value for c

### Step 5: 
print the number of words in text

### Step 6:
end of program

## PROGRAM:
```
#Python word count . . .txt
#developed by: Jai Surya
#registration number: 23002572


from google.colab import drive
drive.mount('/content/drive')
# PYTHON WORD COUNT - .txt file
f=open('/content/drive/My Drive/EXP5.txt','w')
f.write('''Oppenheimer is having a great run at the box office in India. Directed by Christopher Nolan, the film's weekend collection was extremely
 impressive as it minted Rs 60 crore nett. Oppenheimer has been faring better than 'Barbie' in India, unlike the worldwide collections. In India, 'Barbie's'
 opening weekend collection was just around Rs 21 crore.''')
f.close()
f=open('/content/drive/My Drive/EXP5.txt','r')
r1=f.read()
r=r1.split()
c=0
for i in r:
    c+=1
print('Contents of File :',r1,sep='\n')
print('Count :',c)
f.close()
```
### OUTPUT:

![AAA](/AAA.png)


## RESULT:
Thus the program is written to find the word count from a text.
