# Share A Book
I like reading paper books, so I buy them
from amazon. I read them in the span of about
a week and then they sit on my bookshelf for
the rest of my life. I would like to sell them
to someone else that wants to read them, since
they are still in perfect condition, but it is
a hassle.

## Solution
Can we make a service that allows people to share
the books that they buy?

## The Big Idea
Make it so that each user only pays a fraction of the
total cost. If five people read the book, each should
only pay 1/5 of the cost.

It's a chain of purchases. The first user buys a book for
full price, then they sell it for half price. Now there are
two people each paid half the cost. The second person then
sells the book for 1/3 the original price, he gets payment
so that his net cost is a third, and so does the first person.
This pattern continues up till the nth purchase, when someone
decides to keep the book. At that point each person that used
the book has paid 1/n the original price.

The original buyer incurred the most risk, but also got the most
reward since he/she got to use a new book, and got the most
immediate return. The last buyer holds the most power since
they decide whether to end the chain. It's important to make
selling easy since later purchases see slower returns. However,
at the same time the returns at later time are not as important
since the nth buyer got a good price up front.

## View of the User
1. The user wants to buy a book.
2. The user searches the catalog of books.
3. The user buys the most suitable book.
4. The user receives the book in the mail.
5. The user reads the book.
6. The user decides to sell the book to another user.
7. The user posts the book for sale on the catalog.
8. The book sells to another user.
9. The user receives packaging on the mail.
10. The user mails the book to other user.

## Buying a Book
### Buying a book from another user
If a user-seller is selling the desired book, and the
condition of the book and rating of the user-seller
are both satisfactory, then the user-buyer may initiate
a purchase attempt. If the purchase attempt fails, another
user seller with equivalent conditions will be found. If all
attempts fail, the user-buyer will be notified. Another
purchase attempt may be made. If the purchase succeeds, the
user-buyer will receive the book in the mail.

### Buying a new book
If there are no user-sellers selling the book, or if the
books available are not satisfactory, the user-buyer may
purchase a new book. The seller will ship the new book
to the user-buyers.

## Selling a Book
A user that has bought a book from the catalog, has the
right to sell the book to another user. The user becomes
a user-seller. The user-seller must mark the book as for
sale, at which point the user-seller must provide auxiliary
information about the status of the book. After providing
the information, the book will be posted on the catalog.
The book may then be purchased by a user-buyer at any point
in the future. The book may remain in the catalog indefinitely.
The user-seller maintains the book in their possession until
a user-buyer decides to request a purchase. If the status of
the book changes at any point whilst in the catalog, it is
the responsibility of the user-seller to update the condition
of the book. When a purchase is initiated by a user-buyer, the
user-seller will receive a notification, asking for confirmation
of the sale. If the user-seller decides to deny the sale, or
does not respond to the confirmation within the alloted time,
the purchase will be deemed a failure. If the user-seller confirms
the sale, the user-seller will receive packaging in the mail.
The packaging will contain the address of the user-buyer. The
user-seller need only place the book in the packaging and mail
it.

## Keeping a Book
After a purchase a user has the right to keep the book.

## Costs and Payments

### Initial User-Buyer Cost
The user-buyer will pay for shipping costs, and the price of
the book. The price of the book will be the original cost
divided by the number of previous owners plus one. For example,
if the user-buyer is the third person to own the book, the price
will be one-third the original cost. If the user-buyer is the
first person to own the book, then it's a new purchase and
the book is full price.

### Initial User-Seller Payment
The user-seller will receive initial payment equal to the
amount they paid minus the amount the user-buyer paid. For example
if the user-seller paid $100 and the user-buyer paid $50, then
the user-seller will receive payment of $50.

### Other Payments
Every time a book is re-sold, the previous owners get payment
so that the net cost of the purchase is total cost divided
by the new number of buyers.

### Ultimate Cost to the User
The ultimate cost of purchase will be initial cost divided by
the number of users that purchased the book. So if in the
lifetime of a book, it is purchased by 4 users, each user
will have ultimately paid 1/4 of the price.
