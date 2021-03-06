![books](https://user-images.githubusercontent.com/42194815/48988631-dfaecd80-f0fc-11e8-82ec-6737a7880e72.png)

# KnigoPoisk
Find your book

## Ideas
- Roles
  - `Admin` -- **CRUD** with entities, administration, 
  reviews approvals, etc.
    - Add own reviews
    - Approve `User's` reviews
    - Ban `Users`
    - Check reviews
    - Remove reviews
    - Edit reviews (remove profanity, politician aspects)
    - Send warning emails / messages to `Users`
  - User -- **READ/WRITE** access, authentication, reviews, chatting, wishlist, etc.
    - Add reviews
    - Add books to wishlists
    - Chatting (forum?)
    - Rate to books
    - History (what is read) / Timeline
    - Search by categories
  - Client -- **READ/FIND** access
    - Search for books by categories
    - View ratings (e.g. `TOP-500`) 
- Review mechanism
  - `Admin`
    - Approve the reviews
    - Ban users that have troubles with reviews / chats
    - Block users for 1 month / 15 days / forever (?)
  - `Users`
    - Can create reviews / apply for approval
    - Can be banned for review contents
  - `Client`
    - Cannot create reviews / read-only mode   
- Online reading
  - Links to Google books
  - Links to Amazon (to download to Kindle)
- Screen version(s) is any
  - Links to IMDB and Kinopoisk
- Localization / internationalization (2 languages ?)
- Any audiobooks available for this book (what languages ?)
- Links to other web resources (Wiki, Kinopoisk, etc.) -- Admin?
- Relevant/similar books (genre)
- News
- Authors and biographies
- Color themes
- Font sizes
- Quotes
  - User's own quotes (favourites)
  - Wiki-quotes
- Random suggestions
  - Carousel with books that a user can find useful/must read
- Cover
  - Page examples
- Youtube links to reviews and ratings
- Theaters
- Forum ?
- Ratings
    - Top-500
    - Top by rating
    - Mostly reviewed
    - Mostly read
    - ...
- Wishlists
  - Add / edit / remove wishlists
    - Profanity checks
    - Attacks checks (SQL injections, another kinds of code that can break us)
    - Localization (?)

## Project management methodology
- Agile SCRUM

## Technological stack
- Crossbrowsing / UI / markup
  - Bootstrap 4
- IDE
  - IntelliJ IDEA (Community edition)
  - Visual Studio Code
- CI
  - Jenkins / TeamCity / No
- Docker
- Build framework
  - Gradle
- Backend implementation frameworks
  - Spring (Boot)
  - Spring MVC
  - Spring Security
- Validation
  - Hibernate validator
  - Spring MVC OOTB means
- Tests
  - Unit (JUnit, Mockito, Hamcrest matchers)
  - Integration tests (RESTAssured)
  - UI (?)
- ORM / Spring Data (Mongo)
- Environments
  - LOCAL / QA / PROD
- VCS
  - Git
- Client / Server architecture
- OAuth 2.0 (?)
- UI
  - React | VueJS
  - Yarn
  - JavaScript
  - JQuery
- DB
  - MongoDB
- Content
  - Images -- ? (hosting / Docker volume / Akamai)
  
## Wireframes
- Main page
![mainpage](https://user-images.githubusercontent.com/42194815/48996512-cae53080-f122-11e8-81bd-57ed6de70886.png)
