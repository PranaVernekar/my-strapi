

---

# Strapi Local Development Setup

This project is a local instance of the Strapi headless CMS. It includes a custom configuration and a pre-defined **"Post"** collection type to manage content via the Strapi Admin Panel and API.

---

## 🚀 Getting Started

Follow these steps to get the project running on your local machine.

### 1. Installation

Clone the repository to your local machine:

```bash
git clone <your-repo-url>
cd my-project
```

Install the necessary dependencies:

```bash
npm install
```

### 2. Running the Application

Start the development server with auto-reload enabled:

```bash
npm run dev
```

Once the server is running, you can access the project at:

* **Admin Panel:** [http://localhost:1337/admin](http://localhost:1337/admin)
* **API Endpoint:** [http://localhost:1337/api/posts](http://localhost:1337/api/posts)

---

## 🏗 Project Configuration

### Folder Structure

* `src/api/`: Contains the logic, controllers, and services for the content types.
* `src/api/post/content-types/post/schema.json`: Defines the structure of the **Post** collection.
* `config/`: Contains server, database, and security configurations.
* `public/uploads/`: Local storage for uploaded media (images).

---

### Content Type Created: Post

I have created a **Post** collection type with the following fields:

| Field Name    | Type     | Description                  |
| ------------- | -------- | ---------------------------- |
| Title         | Text     | The headline of the post     |
| Description   | Text     | The main body/content        |
| Image         | Media    | Featured image for the post  |
| PublishedDate | Datetime | Date and time of publication |

---

### 🎥 LOOM VIDEO 

A walkthrough of this setup, including folder exploration and content creation, can be found here:

👉 https://www.loom.com/share/12ef40c27ed84578ac84f41fc529082d

---

### 🛠 Tech Stack

* **Framework:** Strapi v4
* **Runtime:** Node.js
* **Package Manager:** npm
* **Database:** SQLite (Default local)

---
