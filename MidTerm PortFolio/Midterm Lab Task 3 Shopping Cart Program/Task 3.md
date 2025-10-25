Modify the menuCart program and include the ff: requirements

1. Validate user choice (if choice is not in the cart) -"display item is not in the cart"

2. Input Customer Name and Age if age is 60 and above provide 20% discount from the total purchased

SOURCE OF CODE:
 
    menu = {"Burger": 35.0,
           "Tacos": 50.0,
           "Fries": 20.0,
           "Tokneneng": 5.0}
    
    cart = []
    total = 0.0
    
    print("---- M E N U ----")
    for key, value in menu.items():
       print(f"{key:15}: P{value:.2f}")
    print("------------------")
     
    while True:
       food = input("Select an item from the menu (q to quit): ")
       if food.lower() == 'q':
           break
       elif food not in menu:
           print("Item is not in the menu, please choose again.")
       else:
           cart.append(food)
    
    if not cart:
       print("No items ordered.")
    else:
       print("\nYour Orders are -----")
       for food in cart:
           total += menu[food]
           print(food, end=" ")
    
       print(f"Subtotal: P{total:.2f}")
    
       name = input("\nEnter Customer Name: ")
       age = int(input("Enter Customer Age: "))
    
       if age >= 60:
           discount = total * 0.20
           total -= discount
           print(f"Senior discount applied (20% off): -P{discount:.2f}")
    
    
       print(f"\nCustomer: {name}")
       print(f"Total Purchased: P{total:.2f}")

<img width="478" height="599" alt="image" src="https://github.com/user-attachments/assets/c5536ee1-1f8a-45a6-bb0b-4cfcd781578d" />
