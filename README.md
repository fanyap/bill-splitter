This is the Bill Splitter App

item.users is an array that returns user who ate the food
item.name is the food
item.price is the price of the food

user.name is the name of the person
user.totalcost
user.items returns an array of items
user.pay_amount

restaurant_bill.users
restaurant_bill.items
restaurant_bill.amount
restaurant_bill.tip
restaurant_bill.tax
restaurant_bill.payers is an array of payers

user has many items through user-items
item has many users through user-items

TABLE user

id | name | total_cost | pay_amount

1   fan    100      30   1

TABLE item

id| name | price | number_of_people

TABLE user-items

id  |   user_id | item_id

user.items

item.users
