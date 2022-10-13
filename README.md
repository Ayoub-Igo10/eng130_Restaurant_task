

# Restaurant Task
When the customer enters the restaurant we want to give them a menu to allow them the choice :First lets start with the menu:
```python
menu = ["salad", "pilau rice", "pizza", "shrimp", "brocolli"]
```
After this has been given we then need to print it so that it's visible and that they're able to read it:
```python
print("In our menu, we have {}, {}, {}, {}, {}".format(menu[0], menu[1], menu[2], menu[3], menu[4]))

```
After this is done we need to create an empty list for the customer to choose what they want.
We now need to allow the customer to choose what they will like and add this to the empty list, to do this we use the append() function.
```python
order_list = []
order = input("Hi What would you like to order? ")
order_list.append(order)
order = input("Anything else? ")
order_list.append(order)
order = input("Anything else? ")
order_list.append(order)
```


