x= float(input("Enter a number of your choise")) 
y=float(input("Enter an another number"))
Add= "+"
Subtract="-"
Multiply= "*"
Division= "/"
symbolchoise= input("choose a symbol to do the deed:'+','-','*','/'")
def deeds(x,y):
    if symbolchoise==Add:
        return x+y
    elif symbolchoise==Subtract:
        return x-y
    elif symbolchoise==Multiply:
        return x*y
    elif symbolchoise==Division:
        return x/y
    else:
        print("something went wrong try again")
print (deeds(x,y))
continue_calculating= True
while continue_calculating is True:
    x= float(input("Enter a number of your choise")) 
    y=float(input("Enter an another number"))
    Add= "+"
    Subtract="-"
    Multiply= "*"
    Division= "/"
    symbolchoise= input("choose a symbol to do the deed:'+','-','*','/'")
    def deeds(x,y):
        if symbolchoise==Add:
            return x+y
        elif symbolchoise==Subtract:
            return x-y
        elif symbolchoise==Multiply:
            return x*y
        elif symbolchoise==Division:
            return x/y
        else:
            print("something went wrong try again")
    print(deeds(x,y))
    stop_deeds= input("would you like to cuntinue doind deeds(yes/no)")
    if stop_deeds=="no":
        continue_calculating= False
print(":)")
