# item-catalog-project
Udacity project.  Item catalog website.

//localhost.com:5000/gconnect"],"javascript_origins":["http://localhost:5000"]}}://localhost.com:5000/gconnect"],"javascript_origins":["http://localhost:5000"]}}://localhost.com:5000/gconnect"],"javascript_origins":["http://localhost:5000"]}}

## Setup:


* Install (if necessary): 
  * [Flask](http://flask.pocoo.org/docs/0.11/installation/)
  * [SQLAlchemy](http://docs.sqlalchemy.org/en/latest/intro.html)

## Testing:

1. Open terminal to folder location of cloned repo.
2. Run database_setup_catalog.py: `python database_setup_catalog.py`
3. Run database_management.py: `python database_management.py`
4. Run catalog.py to start web app: `python catalog.py`
5. Open browser to [http://localhost:5000/category/](http://localhost:5000/category/)


## Expected functionality:
* Users can login / logout Google Plus sign in.
* Users cannot Get or Post New, Edit, or Delete pages without being signed in.
* Users cannot Get or Post Edit or Delete game items without being the original creators of the game item.
* Logged in users can create new game items.
* Can access JSON data at the following pages:
  * Category list: [http://localhost:5000/category/JSON](http://localhost:5000/category/JSON)
  * Specific category's items: [http://localhost:5000/category/\<category_id\>/JSON](http://localhost:5000/category/1/JSON)
  * Specific item information: [http://localhost:5000/category/\<category_id\>/\<item_id\>/JSON](http://localhost:5000/category/1/1/JSON)
