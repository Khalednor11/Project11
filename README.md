# Project11

n=int(input("Enter number: "))
    rev=0
    while(n>0):
        dig=n%10
        rev=rev*10+dig
        n=n//10
    print("Reverse of the number:", rev)

    >>Runtime Test Cases 

    Case 1:
    Enter number: 124
    Reverse of the number: 421

    Case 2:
    Enter number: 4538
    Revese of the number: 8354
