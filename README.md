-->No food delivery.

-->No table reservation

-->The table has different size

-->The restaurant will choose the smallest table which fit the numbers of people(For example, if the party has 3 people, the restaurant would assign a 4-people table instead of a 10-people table)

-->Implement Restaurant Class

Everytime after calling findTable, takeOrder, checkOut, we will userestaurantDescription to test the program.

INPUT->
Input:
meal(10.0)
meal(13.0)
meal(17.0)
table(4)
table(4)
table(10)
party(3)
party(7)
party(4)
party(6)
party(1)
order(1)
order(2, 3)
findTable(1)
findTable(3)
findTable(4)
takeOrder(1, 1)
takeOrder(3, 2)
checkOut(3)
findTable(4)

Output:
Table: 0, table size: 4, isAvailable: false. No current order for this table.
Table: 1, table size: 4, isAvailable: true. No current order for this table.
Table: 2, table size: 10, isAvailable: true. No current order for this table.
*****************************************

Table: 0, table size: 4, isAvailable: false. No current order for this table.
Table: 1, table size: 4, isAvailable: false. No current order for this table.
Table: 2, table size: 10, isAvailable: true. No current order for this table.
*****************************************

Table: 0, table size: 4, isAvailable: false. No current order for this table.
Table: 1, table size: 4, isAvailable: false. No current order for this table.
Table: 2, table size: 10, isAvailable: false. No current order for this table.
*****************************************

Table: 0, table size: 4, isAvailable: false. Order price: 10.0.
Table: 1, table size: 4, isAvailable: false. No current order for this table.
Table: 2, table size: 10, isAvailable: false. No current order for this table.
*****************************************

Table: 0, table size: 4, isAvailable: false. Order price: 10.0.
Table: 1, table size: 4, isAvailable: false. No current order for this table.
Table: 2, table size: 10, isAvailable: false. Order price: 30.0.
*****************************************

Table: 0, table size: 4, isAvailable: false. Order price: 10.0.
Table: 1, table size: 4, isAvailable: false. No current order for this table.
Table: 2, table size: 10, isAvailable: true. No current order for this table.
*****************************************

Table: 0, table size: 4, isAvailable: false. Order price: 10.0.
Table: 1, table size: 4, isAvailable: false. No current order for this table.
Table: 2, table size: 10, isAvailable: false. No current order for this table.
*****************************************

Explanation:
meal(x) means we create a meal, whose price is x.
