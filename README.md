# numberless-hornbill

Create a simple content management system that allows users to add, delete, or update books. Books entered in the system can be viewed in a listing, or searched for using basic searches.

## Context

Creating this web application will provide exposure to:
- Express
- Javascript
- Simple graph database —Neo4j— interactions (Create, Read, Update, Delete)
- Simple server side templating —Jade— (to render data retrieved from the database)

Asterisks (*) denote stretch goals.

## Specifications

- [ ] Any user can add books into the system via an administrative page
- [ ] Books entered in the system are listed on the home page
- [ ] Users can search for books by title 
  - [ ] * User can employ  search operators to narrow results by properties like author, genre, title, et cetera
  - [ ] * Employ "live search" —results are rerendered as the user types in the search field
- [ ] Users can view book details

### Required

- [ ] The artifact produced is properly licensed with the [MIT license](https://opensource.org/licenses/MIT).

## Quality Rubric

- Repo is well mantained —easily inspectable, history is easy to comprehend, branching is employed for discrete features. (Git Flow)
- Code is well formatted without any linting errors
- Variables, functions, css classes, etc. are meaningfully named (no comments exist in code to explain functionality - the names serve that function)
- Functions are small and serve a single purpose
- Code is well organized into a meaningful file structure
- Interface is user friendly
