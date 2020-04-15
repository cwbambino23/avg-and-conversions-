# avg-and-conversions-

#msg = "This program calulates the avg of two numbers"

        #None dynamic program no user inputs 
msg1 = "The number are 5 and 12" 
ans = "The avg of 5 and 12 is:", (5+12)/2

print (msg)
print (msg1)
print (ans) 

        #Dynamic program user inputs
        
num1 = float (input("Enter the first number: "))
num2 = float (input("Enter the second number: "))

print ("The number enter is ", num1 ,"and", num2)
print ("The avg of the numbers", (num1 + num2)/2)

        #This is a program to will convert km to miles 
        
print ("This will convert km to miles: ")
km = float (input("Enter km: "))
print (km, "is", (km * 0.621371), "miles") 

        #Program 2
        
print ("This will convert km to miles: ")
km = float (input("Enter km: "))
mile = km * 0.621371
print (km, "is", round(mile, 2), "miles") 

        #Program 3 
print ("This will convert km to miles: ") #print the statement 
km = float (input("Enter km: ")) #User input the amount of km
mile = km * (1/1.609344) #conversion formula for km toi mile
print (km, "is", round(mile, 2), "miles") #print the conversion in miles

Take the avg of 2 numbers and the conversion to km to miles
