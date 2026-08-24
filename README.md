<div align="center">

# 💬 Quora Lite

**A lightweight community Q&A platform built with Node.js, Express, and EJS — featuring full CRUD operations and RESTful routing.**

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![EJS](https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=black)](https://ejs.co/)

</div>

---

## ✨ Features

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📝 Post Management</h4>
      <ul>
        <li><b>Create:</b> Publish new Q&A posts with title and content</li>
        <li><b>Read:</b> Browse all posts or view individual post details</li>
        <li><b>Update:</b> Edit existing posts with pre-populated forms</li>
        <li><b>Delete:</b> Remove posts with proper route handling</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🏗️ Architecture</h4>
      <ul>
        <li><b>RESTful Routes:</b> Proper HTTP method usage (GET, POST, PATCH, DELETE)</li>
        <li><b>Server-Side Rendering:</b> Dynamic HTML via EJS templates</li>
        <li><b>UUID Generation:</b> Unique identifiers for each post</li>
        <li><b>Method Override:</b> PATCH/DELETE support via <code>method-override</code></li>
      </ul>
    </td>
  </tr>
</table>

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/Deep-0208/Quora-Lite.git
cd Quora-Lite

# Install dependencies
npm install

# Start the server
node index.js

# Open in browser
# http://localhost:8080/posts
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **Node.js** | JavaScript runtime |
| **Express.js** | Web framework & routing |
| **EJS** | Server-side template engine |
| **method-override** | HTTP method spoofing for PATCH/DELETE |
| **UUID** | Unique post identifier generation |

---

## 🏗️ Project Structure

```text
Quora-Lite/
├── index.js            # Express server & route definitions
├── package.json        # Dependencies & scripts
├── views/              # EJS templates
│   ├── index.ejs       # All posts listing
│   ├── show.ejs        # Individual post view
│   ├── new.ejs         # Create post form
│   └── edit.ejs        # Edit post form
└── public/             # Static assets (CSS)
```

---

## 📡 API Routes

| Method | Endpoint | Action |
| :---: | :--- | :--- |
| `GET` | `/posts` | List all posts |
| `GET` | `/posts/new` | Render create form |
| `POST` | `/posts` | Create new post |
| `GET` | `/posts/:id` | View single post |
| `GET` | `/posts/:id/edit` | Render edit form |
| `PATCH` | `/posts/:id` | Update post |
| `DELETE` | `/posts/:id` | Delete post |

---

## 📄 License

Open source — feel free to fork and build on top of this project.

---

<div align="center">
  <strong>Built by <a href="https://github.com/Deep-0208">Deep Panchal</a></strong>
</div>
