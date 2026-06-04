This is a simple Java console based application to manage warehouse inventory using ArrayList.

We can add
- Add new items
- Remove items
- Update item quantity
- Search items by ID or name
- Display all items


We need to compile first using "javac Warehouse.java" command

Then we can run it using "java Warehouse" command.

Sample output

1. Add Item
2. Remove Item
3. Update Quantity
4. Search Item
5. Display All
6. Exit
Enter choice: 1
Enter ID: 1
Enter Name: Mobile
Enter Quantity: 10
Enter Price: 10000
Item added

1. Add Item
2. Remove Item
3. Update Quantity
4. Search Item
5. Display All
6. Exit
Enter choice: 3
Enter ID: 1
Enter new quantity: 20
Quantity updated

1. Add Item
2. Remove Item
3. Update Quantity
4. Search Item
5. Display All
6. Exit
Enter choice: 5
ID: 1 | Name: Mobile | Qty: 20 | Price: 10000.0

1. Add Item
2. Remove Item
3. Update Quantity
4. Search Item
5. Display All
6. Exit
Enter choice: 4
Enter ID or Name: Mobile
ID: 1 | Name: Mobile | Qty: 20 | Price: 10000.0

1. Add Item
2. Remove Item
3. Update Quantity
4. Search Item
5. Display All
6. Exit
Enter choice: 2
Enter ID: 1
Item removed

1. Add Item
2. Remove Item
3. Update Quantity
4. Search Item
5. Display All
6. Exit
Enter choice: 5
Inventory is empty

1. Add Item
2. Remove Item
3. Update Quantity
4. Search Item
5. Display All
6. Exit
Enter choice: 6
Exiting...