# guess-a-number-inpython
this is a fun game for guessing the number
i=18
guess=1 
print("you have nine chance to enter the number")
while(guess<=9):
    v1=int(input("enter the number for guessing"))
    if(v1>i):
        
        print("your number is greater the number")
        # continue
    if(v1<i):
        print("your numberr is less than the number")
        # continue
    if(v1==18):
        print("yoy you entered the correct number")
        print(guess,"no of gyesses you have taken")
        break
    
    print( 9-guess,"you have left with these chances")
    guess=guess+1
    
    if(guess>9):
        print("game over")
