# blog-interface
This is a project that aims to demonstrate knowledge in Laravel by developing a blog.

Requirements Document - Blog with Comment System

1. Introduction

This document describes the functional and non-functional requirements for the development of a blog system with a comment system. The goal is to allow users to publish, view and comment on posts.

2. Functional Requirements

2.1. User Registration and Authentication

RF01: The system should allow users to register with the following fields: name, email and password.

RF02: The system should allow users to log in with email and password.

RF03: The system should offer the option of password recovery via email.

2.2. Post Management

RF04: The system should allow authenticated users to create, edit and delete posts.

RF05: Each post should have a title, content and image upload option.

RF06: The system should display a list of posts in reverse chronological order.

RF07: The system shall allow searching for posts by title or content.

RF08: Posts shall be categorized by tags.

2.3. Comment System

RF09: The system shall allow authenticated users to comment on posts.

RF10: Comments shall be associated with a specific post.

RF11: The system shall display comments in chronological order.

RF12: The author of a comment shall be able to edit or delete his/her comment.

2.4. User Interface

RF13: The system shall have a home page that displays the most recent posts.

RF14: The system shall have a post detail page that displays the post content and its comments.

RF15: The system shall allow users to filter posts by tags.

3. Non-Functional Requirements

3.1. Performance

RNF01: The system shall load the list of posts within 2 seconds.

3.2. Usability

RNF02: The system must be responsive and work on mobile and desktop devices.

RNF03: The system must use an intuitive interface based on Bootstrap.

3.3. Security

RNF04: User passwords must be stored in encrypted form.

RNF05: The system must protect against SQL Injection and Cross-Site Scripting (XSS) attacks.

3.4. Maintenance

RNF06: The system must be developed following Laravel framework standards to facilitate maintenance and expansion.

4. Technologies

Language: PHP 8.2+

Framework: Laravel 10

Database: MySQL 8

Frontend: Blade templates, Bootstrap 5

Version Control: Git/GitHub

5. Proposed Schedule

Week 1: Initial project setup and authentication implementation.

Week 2: CRUD development for posts.

Week 3: Implementation of the comment system.

Week 4: Refinement of the user interface and final testing.

6. Final Considerations

This document aims to guide the development of the project in a clear and organized manner. Additional requirements may be incorporated upon validation of the initial scope.
