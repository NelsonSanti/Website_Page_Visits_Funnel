# Website Page Visits Funnel

In this exercise, I analyzed data on visits to an imaginary **Shirt company's website**.
The aim is to build a funnel, which is a description of how many people continue to the next step of a multi-step process.

In this case, the funnel describes the following process:
- A user visits ShirtCompany.com
- A user adds a t-shirt to their cart
- A user clicks "checkout"
- A user actually purchases a t-shirt

The exercise ends with data information that reveals:
- The percentage of users that visited the website but ***ended up not placing a t-shirt in their cart***
- The percentage of users that put items in their cart, but ***did not proceed to checkout***
- The percentage of users proceeded to checkout, but ***did not purchase a t-shirt***
- A suggestion to fix the problems found

I used four DataFrames for this exercise:
- `visits`: lists all of the users who have visited the website
- `cart`: lists all of the users who have added a t-shirt to their cart
- `checkout`: lists all of the users who have started the checkout
- `purchase`: lists all of the users who have purchased a t-shirt

## Technologies used
- Python Programming Language
- Pandas
- Jupyter Notebook
