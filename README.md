Shopping list app. 

in this app, i learned to use the list ADT to manage a sorted shopping list. 

Programming to an interface. to do this you declare the list as this:
ListInterface<ShoppingItem> shoppingList = new ArrayBasedList<>();

this means you can swtich the implentation with just one line. 
from new ArrayBasedList<>() to new LinkedBasedList<>();
the code words fine with either implementaion. 

Using the list ADT as an abstraction. this list ADT lets you use operations like:
add(), get(), remove() and iterator() without telling you how they work internally. 
so you can focus on what operations you need not how they are implenented. 
