Web Gallery


## 📸 Secure Image Gallery Web Application

This project is a **responsive, interactive image gallery web application** built with **HTML, CSS, and JavaScript**, designed to provide users with a secure and organized way to manage and view images. It includes support for multiple users with private storage areas, folder-based organization, and a built-in password reset mechanism using a custom reminder system.

### 🔐 Key Features

* **Multi-user Registration & Login System**

  * Users can register with a username and password.
  * Includes a "password reminder" field for password reset functionality.
  * Login system securely manages sessions using browser `localStorage`.

* **Private Image Storage**

  * After logging in, users get access to a **Private** section where they can upload and view their private images.
  * These images are isolated per user and not visible to others.

* **Public Image Gallery**

  * The **All Images** section allows users to view a set of publicly available images.
  * New images can be added to this section via an upload button.

* **Folder-based Organization**

  * Users can create custom folders to organize images.
  * Upload images into specific folders and view them separately.

* **Beautiful UI & Responsive Design**

  * Built with modern CSS styling (gradient backgrounds, animations, modals).
  * Fully responsive for various screen sizes.
  * Interactive image preview modals with captions and accessibility support.

* **Secure Password Reset**

  * Users can reset their password by providing the username and the password reminder phrase.

### 📁 Technologies Used

* **HTML5** – For structure and semantic layout.
* **CSS3** – For advanced styling, animations, and responsive design.
* **Vanilla JavaScript (ES6+)** – For interactivity, data storage, and logic.
* **LocalStorage API** – To persist user data and images between sessions.

  🚀 How It Works

1. On first load, public images are shown.
2. Users can:

   * View all images.
   * Create folders and organize images.
   * Register/login to access their private space.
3. Uploaded images are stored as Base64 strings in the browser's `localStorage`, ensuring persistence without a backend.
4. Users can log out, reset their password, or switch accounts.

  🌟 Optional Enhancements (Future Scope)

* Add backend support (Node.js, MongoDB) for real database persistence.
* Add drag-and-drop upload support.
* Implement roles or admin panel to manage public content.
* Enable real-time syncing across devices.

 
