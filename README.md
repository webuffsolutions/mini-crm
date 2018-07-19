# Mini CRM

## Instructions

1. Follow the requirements as detailed below
2. It is not required for you to finish all the parts.
3. Compress your files (ZIP) and send it to info@webuffsolutions.com

## Requirements

### Basically, you are tasked to create a project to manage companies and their employees. Mini CRM.

-	Basic Laravel Auth: ability to log in as administrator
- Use database seeds to create first user with email admin@admin.com and password “password”
-	CRUD functionality (Create / Read / Update / Delete) for two menu items: Companies and Employees.
-	Companies DB table consists of these fields: Name (required), email, logo (minimum 100×100), website
-	Employees DB table consists of these fields: First name (required), last name (required), Company (foreign key to Companies), email, phone
-	Use database migrations to create those schemas above
-	Store companies logos in app/public/uploads folder
-	Use basic Laravel resource controllers with default methods – index, create, store etc.
-	Use Laravel’s validation function, using Request classes
-	Use Laravel’s pagination for showing Companies/Employees list, 10 entries per page
-	Use Laravel make:auth as default Bootstrap-based design theme, but remove ability to register
- Modify default login page layout

## Rules/Pointers:
- Clearly written code is a big plus
- Bonus: Ajax Implementation, TDD, Repository Pattern, Use of other frontend frameworks like semantic-ui, bulma-css, materialize css, etc
- Put comments on your code
