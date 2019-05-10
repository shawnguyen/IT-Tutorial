# IT Tutorial: Making an Array in Python
## Shawn Nguyen
### An array is a variable that gives you the ability to hold more than one variable within a variable at a time. By doing this, it helps saving time and organization.
#### Target Audience: Beginner Level

**Scenario:** You work at sports department store that carries multiple athletic clothing brands from Nike, Adidas, and many more. You were assigned to separate the t-shirts by brand through a Python code.

- Brands: Nike, Adidas, Under Armour, New Balance, Li Ning, Jordan Brand, Champion, Puma, Reebok, and Anta

**Example:** Creating the array

`Brands = ["Nike", "Adidas", "Under Armour", "New Balance", "Li Ning", "Jordan Brand", "Champion", "Puma", "Reebok", "Anta"]`

- "Brands" is the name of the array. It can be named whatever you wish it to be.

- The array index starts at zero (0). Meaning the index of Nike would be zero (0) since it is the first one in the list of the array.

**Example:** Accessing an element of an array

`x = Brands[1]`

- "x" is just the name of the variable. It can be named whatever you wish it to be.

- "Brands" calls for the array Brands.

- "[1]" calls for the string in the index one (1) of the array Brands.

**Example:** Printing the array

*Printing a specific brand:*

```
Brands = ["Nike", "Adidas", "Under Armour", "New Balance", "Li Ning", "Jordan Brand", "Champion", "Puma", "Reebok", "Anta"]

x = Brands[1]

print("Selected brand:")

print(x)
```

*Output:*

```
Brand selected: Adidas
```

___

*Printing all brands:*

```
Brands = ["Nike", "Adidas", "Under Armour", "New Balance", "Li Ning", "Jordan Brand", "Champion", "Puma", "Reebok", "Anta"]

print("All brands:")

for x in Brands:
  print(x)
```

*Output:*

```
All brands:
Nike
Adidas
Under Armour
New Balance
Li Ning
Jordan Brand
Champion
Puma
Reebok
Anta
```

___

**TRY IT YOURSELF!**

**Scenario:** You work a video game store and just got a new shipment of games. You are assigned to organization all the game into different categories within a Python code.

- Genres: Sports, RPGs, Shooters, Action/Adventure, Racing, and Children

Then print out the outputs!
