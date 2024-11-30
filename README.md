menu={'pizza':40,
      'Pasta':50,
      
      'salad':70,
      'samosa':50,
      'musambi juice':60


      
}
print("welcome the  CPP Hotel")
print("Here is the Menu for you ")
print("pizza:40\npasta:50\nsalad:70\nsamosa:50\nmusambi juice:60")

order_total= 0
item1= input("Enter the item for the above menu ")
if item1 in menu:
    order_total +=menu[item1]
    print(f" {item1} has been added to order ")
else:
    print(f"{item1} is not available yet ")


another_item=input("Do you want to order another item form menu(yes/no) ")
if another_item=="yes":
    item2=input("Enter the another item ")
    if item2 in menu :
            order_total +=menu[item2]
            print(f" {item2} has been added to order ")
    else:
            print(f" {item2} is not available ")

print(f"total amount to pay is {order_total} ")
print(f"Thanku you for coming to our hotel ")

    
