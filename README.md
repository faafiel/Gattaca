# Gattaca
Personal Storage

# -*- coding: utf-8 -*-

#Fair Value in Futures Contract (Commodities) Formula
print ("Fair Value in Futures Contract (Commodities) Formula\nPlease input your values.\n")

#Defining global vars
x=float(input("Spot Price :",))        
y=float(input("Interest Rate :",))     
z=float(input("Storage Cost :",))      

#Defining the finance formula and what vars to use
def Fair_Value_in_Commodities_Futures_Contract():
    global x, y, z
    return x*(1+y+z)

#Calling the result of the formula
res1=Fair_Value_in_Commodities_Futures_Contract()
print("Fair Value =", res1)

input("Please press ENTER to exit")
