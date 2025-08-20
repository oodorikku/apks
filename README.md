> Both apps have incomplete UI, sole purpose of these projects is to learn about firebase, notifications, REST APIs and payments.

[Figma file](https://www.figma.com/design/cJLWiTPuxWvsEVm9xWv7Gg/eCommerce-app?node-id=0-1&t=M622EPt4GtY7VwnS-1) 

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
      - firebase notification when payment is successful (only works if Replit server is running)
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

Admin side account for testing:   
Email: audric_ang@dlsu.edu.ph  
Password: 123456  

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

### Recipe app
> This is a flutter remake of my very first app made with Java
- Search function with some filters (can only search what you can cook with your chosen ingredients, not the direct recipe name)
  - fetch data from Spoonacular API
- Add and store ingredients to pantry
- Save recipe in pdf format
- Share recipe link
- Download a recipe (local only, sqlite storage)
  - Filter alphabetically or by date added
- Create a meal plan based on diet and total calorie
  - ~~save meal plan on calendar type~~
