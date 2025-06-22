> Both apps have incomplete UI, sole purpose of these projects is to learn about firebase and APIs

### Buyer side
- Firebase auth
  - email verification
  - forgot password
- product category filter
- top products
- search function with filtering (needs improvement for larger scale database)
- liked products
- cart
  - edit quantity / delete
  - checkout
  - payment with paymongo (needs to add more options such as paypal)
      - firebase notification when payment is successful
      - moved to reserved orders if payment failed
- user account
  - change name, password, phone
- order(s) page
  - to pay, pending, on-going, completed
  - order details
- light/dark/system theme
- ~~credit cards~~
- address book
- notifications

### Admin side
- Firebase auth
  - single device login
- role based access
  - e.g. Product manager cannot access orders
- Add/edit/delete products
- View/change progress of order with notification to specific buyer
- View sales summary (not implemented)
- Logs (add/edit/delete products)
- Accounts (for admin side only)
- Send notification (implement sending to specific person)
- Add/delete news banner (fix size ratio)
