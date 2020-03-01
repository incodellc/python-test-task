# Interview test task for Python developers

### Goal
Develop user profile page with posts on it. Every post may contain one or multiple comments.
Optional: comments may contain other comments (responses).

### Prerequisites
It’s being expected to have (at least) the following pages:
• login/sign up pages;
• user profile page.

### Login page
**Description:** Contains username/email and password fields and at least 1 social network 3rd-party API integration (e.g. Facebook, Google, Twitter) for user authentication. Applying basic/advanced form fields validation business-logic would be a plus.
**Functionality:** Authenticates users in the application. If logged in, do a redirect to the user profile page automatically.

### Sign up page
**Description:** Contains username, email, password, and repeat password form fields. Applying basic/advanced form fields validation business-logic would be a plus.
**Functionality:** If submitted correctly, creates a new user with specified username and/or email address and password. Social network authentication integrations will be highly appreciated here as well.

### User profile page
**Description:** Users can visit other profile pages using user IDs. Each user profile page contains user information (email, username) and posts/comments published on that wall accordingly. It’s possible to access this page as an authenticated or non-authenticated user.
**Functionality**: If not authenticated, you're only allowed:
- to see user-related information;
- to see posts located on this "wall".

Therefore if authenticated, you can:
- do the same stuff as a non-authenticated user;
- create/delete/edit own posts/comments on this page

Infinity-scroll and/or load more buttons functionality implemented on this page will be a plus.

## Requirements
1. **UI**:
    Candidate can use any available technologies (JS, HTML5/CSS3, LESS/SASS/SCSS), libraries and frameworks to implement described functionality.
2. **Design**:
    Layouts are arbitrary with minimal customization. Candidate can deliver his/her vision in terms of building and styling layouts for those pages listed in the description.
3. **Database**:
    Any SQL/NoSQL DBMS is acceptable. Migrations have to be configured properly if needed.
4. **Frameworks**:
    You are allowed to use any of the existing frameworks such as Django, Flask etc.
5. **Code quality**:
    Produced codebase should be clean and maintainable. Feel free to use comments to describe specific classes and functions in your code.

**Application should be installable and 100% workable.**

## Once Complete
1. Commit and Push your code to your new repository.
2. Send us a pull request. We will review your code and get back to you.
