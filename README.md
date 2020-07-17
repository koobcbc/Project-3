# Project-3

# Description
- Due to covid, many ice cream parlors are not allowing customers in their store. However we have created an online app where customers can place an order for pickup allowing them to enjoy a delicious treat of their choice. We can bring your your morning, mid-day or late night cravings to life. If you have already placed an order you can check your past order by looking for your name and your order will be displayed.

# Project Links 
- frontend git 
- [backend git]()

# Wireframs/Architecture
- [WireFrame](https://www.figma.com/file/3PGHU4ez2A2nW7BCGAuUYr/icecream-app?node-id=12%3A4)
- [React Architecture](https://imgur.com/vyTQGPH)

# Time Priority Matrix/Chart
  
| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Create Model | E | 1hr| n/a | n/a |
| Create Controller | M | 1 hour| n/a | n/a |
| Setup Server | E | .5hr| n/a | n/a |
| Set up Conections  | E | .5hr| n/a | n/a |
| create Seed File  | M | 1hrs| n/a | n/a |
| Research  | E | 2hrs| n/a | n/a |
| Total | H | 6hrs| n/a| n/a|

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Create react app and components| H | .5hr| - | - |
| Install packages and Set up React Routing | H | .5hr| - | - |
| Make APIcall from App | H | .5hr| - | - |
| Set up the layout components (Header, NavBar, Footer) | H | .5hr | - | - |
| Home component | H | 1hr| - | - |
| New order component | H | 2hr| - | - |
| Functionality of order form | H | 5hr| - | - |
| make delete / filter functionality in Past Order | H | 2.5hrs| - | - |
| Basic Styling for nav, footer, about page | H | 2hrs| - | - |
| Basic Styling for main | H | 10hrs| - | - |
| Additional Styling (effects) for the page | M | 2hrs| - | - |
| Total | H | 26.5hrs| -| -|

# MVP / POSTMVP 
- MVP specifications (Group) 

## Components description
- Header
  - Shared component that sits at the top of the page and contains site title/tagline/logo
- Nav
  Shared component right below Header, contains links to the components Home, New Order, annd Past - - - Order
- Home
  - Simple landing page with graphic/tagline/eetc.
- New Order
   - Page with form that allows you to fill out your order. Options for names, toppings, cone, bowl,etc.
- Past Orders
   - The past orders will all be stored in the backend. This page will render a list of past orders with name and date. Clicking on an order will take you to an Order page.
- Order
  - Page that contains all the details of a specifiv past order.
- About
  - This will be the "Team Page" with photos and descriptions of everyone that worked on the project
- Footer
  - Shared component with copyright info etc.


# Backend Description
- models/Schemas. (Alex, Joe)

- The Milkshakes Schema will contain keys with the value of flavor, toppings, size and price. The flavors, toppings and size values will be set to String and the value of price will be set to Number.

# Additional libraries
- Axios
- React
- Node
- Express

# Code Snippet 
- project code 

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```
