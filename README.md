### 

<!-- KAMILA'S MINIPROJECT 
sob 28 29 30 

#first i'll try to do the 'first triangle' where i represents the number of rows and j the number of columns

for i in range (0,6):
    for j in range (i): #so in order to not get the same amount of stars in every row i can control the range by changing it from the numbers of line to i, in this case i can make all the rows have different amount of stars
        print('*', end='') #la parola end serve per assicurare che ci sia uno spazio dopo ogni start
    print('')

n= 4;
for l in range(n):
    for c in range(l, n):
        print('*', end='')  # ' end='' ' is used to make sure i have a space after every star
    print('')

#sob 29

#i divided the task in two part, the first concerned making the code for the upper part of the pattern (from line 32 to line 38) while from line 39 down code was focused on the lower part of the pattern 

#this exercise consisted of showing the movement of the 'stars' without using tha range fuction, but using the code from the previous exercise  
#in order to do so i had to use lists, which in this case represent list column represent the movement on the x axis and and the other two lists represent the movement on the y axis (listrow for the upper part of the project and listrow1 for the lower one)
#the reason why i did that was because dividing the task in smaller parts makes it easier to work on and fix any mistakes 

listcolumn = [0,1,2,3,4]
listrow = [0,1,2,3]
listrow1 = [0,1,2,3,4]


for i in listrow: 
    for j in listcolumn:
        if i==j:
            print('*',end='')
        else:
            print(" ", end='')
    print() #if we run the code here we'll see the first part of the pattern showing stopping just before the vertex of the 'pyramid'
n=4;
for j in listcolumn:
    for i in listrow1:
        if i+j==n:
            print('*', end='')
        else:
            print(" ", end='')
    print()

-->
