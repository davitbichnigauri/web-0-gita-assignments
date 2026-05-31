### ✅ **Complex HTML Structure for Practice**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Parent-Child-Sibling Practice</title>
  </head>
  <body>
    <div id="main-container">
      <h1>Welcome to the Practice Page</h1>

      <div class="section" id="profile-section">
        <h2>User Profile</h2>
        <div class="profile-card">
          <span class="username">JohnDoe123</span>
          <span class="email">john@example.com</span>
          <div class="avatar">
            <img src="avatar.jpg" alt="User Avatar" />
          </div>
        </div>
      </div>

      <div class="section" id="posts-section">
        <h2>Recent Posts</h2>

        <div class="post">
          <h3>Post Title 1</h3>
          <p>This is the first post content.</p>
          <span class="date">Posted on: 2025-04-11</span>
        </div>

        <div class="post">
          <h3>Post Title 2</h3>
          <p>This is the second post content.</p>
          <span class="date">Posted on: 2025-04-10</span>
        </div>
      </div>

      <div class="section" id="friends-section">
        <h2>Friends List</h2>
        <ul>
          <li>
            <span class="friend-name">Alice</span>
            <span class="status online">Online</span>
          </li>
          <li>
            <span class="friend-name">Bob</span>
            <span class="status offline">Offline</span>
          </li>
        </ul>
      </div>

      <footer>
        <p>© 2025 MyPracticeSite</p>
      </footer>
    </div>
  </body>
</html>
```

---

### 📘 Ideas for Questions:

1. **Which element is the parent of `<h2>User Profile</h2>`?**
2. **Is `.email` a sibling of `.username`?**
3. **Who is the parent of all `.post` elements?**
4. **What are the children of `#friends-section`?**
5. **Is `<footer>` a sibling of `#profile-section`?**
6. **Is `.avatar` a descendant of `#main-container`?**
7. **What is the direct child of `ul`?**

---

### 📘 პასუხები:

1. **რომელი ელემენტია `<h2>User Profile</h2>`-ის მშობელი (parent)?**
    * `<div class="section" id="profile-section">`
2. **არის თუ არა `.email` `.username`-ის და-ძმა (sibling)?**
    * დიახ, ორივე ერთსა და იმავე მშობელ ელემენტში (`.profile-card`) ზის.
3. **ვინ არის ყველა `.post` ელემენტის მშობელი (parent)?**
    * `<div class="section" id="posts-section">`
4. **რა არის `#friends-section`-ის შვილები (children)?**
    * `<h2>Friends List</h2>` და `<ul>`
5. **არის თუ არა `<footer>` `#profile-section`-ის და-ძმა (sibling)?**
    * დიახ, ორივეს საერთო მშობელი ჰყავს (`#main-container`).
6. **არის თუ არა `.avatar` `#main-container`-ის შთამომავალი (descendant)?**
    * დიახ, ის იმყოფება კონტეინერის შიგნით (უფრო ღრმა დონეზე).
7. **რა არის `ul`-ის პირდაპირი შვილი (direct child)?**
    * `<li>` ელემენტები.
