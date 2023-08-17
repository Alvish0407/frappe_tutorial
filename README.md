## Library Management System

Frappe Framework Tutorial

Follow [this](https://frappeframework.com/docs/user/en/tutorial) guide to create a web application from scratch using the Frappe Framework.

### **What are we building?**

We will build a simple **Library Management System** in which the **Librarian** can log in and manage Articles and Memberships. We will build the following models:

1. **Article**: A Book or similar item that can be rented.
2. **Library Member**: A user who is subscribed to a membership.
3. **Library Transaction**: An Issue or Return of an article.
4. **Library Membership**: A document that represents an active membership of a Library Member.
5. **Library Settings**: Settings that define values like Loan Period and the maximum number of articles that can be issued at a time.

The Librarian will log in to an interface known as **Desk**, a rich admin interface that ships with the framework. The Desk provides many standard views like List view, Form view, Report view, etc, and many features like Role-based Permissions.

We will also create public Web Views which can be accessed by the Library Members where they can browse available Articles.

#### License

MIT
