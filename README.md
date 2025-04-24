---

# 📇 Contacts App

A simple and intuitive React-based application to manage your personal contacts. Users can add new contacts, view existing ones, and mark favorites with a single click.

---

## 🔗 Live Demo

<a href="https://contlistfavnag.ccbp.tech/" target="_blank">
  <img    src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExYmMwNjhtajFwNDdrbDNicXN5Y3Y3OGw5ZXZhMDhkemF4M2ZxdHZjNSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/mBRLcBE5qCbe1xvwQ3/giphy.gif" 
    alt="Visit On-Demand Projects Showcase" 
    width="300" 
    height="300"
  />
</a>

> Click the GIF above to launch the app!

---


## 🚀 Features

- ➕ **Add Contacts** – Enter name and mobile number to add new contacts
- ⭐ **Favorite Toggle** – Click on the star icon to mark/unmark contacts as favorites
- 📱 **Responsive UI** – Clean layout optimized for both desktop and mobile
- 🔄 **Auto-Generated Unique IDs** using `uuid` for each contact

## 🛠️ Tech Stack

- **Frontend**: React
- **JavaScript**: ES6+
- **CSS**: Flexbox for responsive layouts
- **UUID**: For generating unique contact IDs

## 📂 Project Structure

```
contacts-app/
├── components/
│   └── ContactItem.js         # Single contact display with favorite toggle
├── App.js                     # Main application logic
├── App.css                    # Styling for the app layout
├── index.js                   # Entry point
└── index.css                  # Global styles
```

## 🧑‍💻 How to Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/your-username/contacts-app.git
cd contacts-app
```

2. **Install dependencies**

```bash
npm install
```

3. **Run the application**

```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📸 UI Preview

| Add Contacts | View Contacts |
|--------------|----------------|
| ![Add Contact](https://user-images.githubusercontent.com/000000/0000000/add-contact.gif) | ![View Contact](https://user-images.githubusercontent.com/000000/0000000/view-contact.gif) |

## 🧩 Key Components

### `App.js`

- Manages state for contact list, form inputs
- Handles contact addition and toggling favorites

### `ContactItem.js`

- Renders individual contact info
- Displays favorite icon based on `isFavorite`

## 📦 Dependencies

- `react`
- `uuid`

## ✨ Future Improvements

- Search functionality for filtering contacts
- Option to delete contacts
- LocalStorage integration for data persistence

---

> Made with ❤️ using React.  
> Feel free to fork and improve it!

---
