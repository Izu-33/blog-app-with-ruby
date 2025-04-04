# Basic CRUD App (People and Posts)

This is a very basic Ruby on Rails application demonstrating Create, Read, Update, and Delete (CRUD) functionality for two models: `People` and `Posts`.

## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd your_repository_name
    ```
    *(Replace `<repository_url>` with the actual URL of your Git repository)*

2.  **Install dependencies:**
    ```bash
    bundle install
    ```

3.  **Set up the database:**
    ```bash
    rails db:create
    rails db:migrate
    ```

4.  **Start the Rails server:**
    ```bash
    rails server
    ```

5.  **Access the application:** Open your web browser and navigate to `http://localhost:3000`.

## Functionality

This application allows you to:

* **Manage People:**
    * Create new people.
    * View a list of people.
    * View details of a specific person.
    * Edit existing people.
    * Delete people.

* **Manage Posts:**
    * Create new posts.
    * View a list of posts.
    * View details of a specific post.
    * Edit existing posts.
    * Delete posts.

## Models

* **Person:** Represents an individual. Likely has attributes such as `name` and other relevant details.
* **Post:** Represents a blog post or similar content. Likely has attributes such as `title` and `body`.

## Further Development

This is a basic starting point. You can expand this application by adding features such as:

* User authentication.
* Relationships between People and Posts (e.g., a Person can have many Posts).
* More advanced UI elements.
* Testing.
