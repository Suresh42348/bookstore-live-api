//page1

list of all categories=> https://frozen-meadow-35944.herokuapp.com/category                         localhost:9800/category
list of all books=> https://frozen-meadow-35944.herokuapp.com/books                                 localhost:9800/books



//page2
list of books based categoryid=> https://frozen-meadow-35944.herokuapp.com/books?categoryid=1       localhost:9800/books/categoryid=1
list of books based on bookid=>https://frozen-meadow-35944.herokuapp.com/books?bookid=1             localhost:9800/books/bookid=1



details of books based on bookid or category id
=> https://frozen-meadow-35944.herokuapp.com/books?categoryid=1                                        localhost:9800/details?categoryid=1

=> https://frozen-meadow-35944.herokuapp.com/books?categoryid=1                                        localhost:9800/details?bookid=1


Filter on basis of date of book launch=>
Filter on basis of price Low to High=>
Filter on basis of price High to Low=>
sorting(letter: A-Z)=>
sorting(letter: a-z)=>


//page3
Place Order (post)=> localhost:9700/placeOrder (body) > { "name":"suresh", "email":"suresh@gmail.com", "address":"Hno 23,Sector 1", "phone":945645656, "cost":600, "bookid":[4,6,7], "status":"Pending" }

//page4
See all order placed=>
Get Order on basis of emailId
https://frozen-meadow-35944.herokuapp.com/viewOrder?email=suresh@gmail.com
localhost:9800/viewOrder?email=suresh@gmail.com

delete orders based on orderid
https://frozen-meadow-35944.herokuapp.com/deleteorder?id=1234

//page 5
add to cart
https://frozen-meadow-35944.herokuapp.com/cart (body) > { "name":"suresh", "email":"suresh@gmail.com", "address":"Hno 23,Sector 1", "phone":945645656, "cost":600, "bookid":[4,6,7], "status":"Pending","cid":4566 }

view cart 
tps://frozen-meadow-35944.herokuapp.com/viewcart?email=panku42348@gmail.com

remove from cart
https://frozen-meadow-35944.herokuapp.com/removefromcart?cid=4566






