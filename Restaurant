# Restaurant Management System

menu = {
    "Burger": 120,
    "Pizza": 250,
    "Pasta": 180,
    "Sandwich": 100,
    "Cold Drink": 50
}

print("===== WELCOME TO RESTAURANT =====")
print("\nMenu:")
for item, price in menu.items():
    print(f"{item} - Rs.{price}")

total_bill = 0

while True:
    item = input("\nEnter item name: ")

    if item in menu:
        quantity = int(input("Enter quantity: "))
        cost = menu[item] * quantity
        total_bill += cost
        print(f"{item} x {quantity} = Rs.{cost}")
    else:
        print("Item not available!")

    choice = input("Do you want to order more? (yes/no): ").lower()

    if choice != "yes":
        break

print("\n===== BILL =====")
print(f"Total Amount = Rs.{total_bill}")
print("Thank You! Visit Again.")
