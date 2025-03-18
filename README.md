### **DocSync** 📒🚀  
A simple **note-taking application** with **automatic saving**, built using **React (Vite) + Redux**, and deployed on **Vercel**.  

🌍 **Live URL:** [DocSync](https://docsync-chi.vercel.app/login)  
📂 **Frontend Repository:** [GitHub - docSyncF](https://github.com/subhash1107/docSyncF)  

---

## **Features** ✨  
✅ **User Authentication** – Login & logout with correct toast messages.  
✅ **Automatic Saving** – Notes are saved automatically **2-3 seconds after typing**.  
✅ **State Management** – Uses **Redux Toolkit** for global state.  
✅ **Form Validation** – Integrated with **Formik & Yup**.  
✅ **Responsive UI** – Optimized for all screen sizes.  
✅ **Loading Indicator** – Shows a top loading bar for better UX.  

---

## **Tech Stack** 🛠️  
### **Frontend:**  
- ⚡ **React (Vite) 19** – Fast frontend framework  
- 🛠 **Redux Toolkit** – State management  
- 🔀 **React Router DOM** – Navigation handling  
- 🍪 **JS-Cookie** – Manages authentication tokens  
- 🎨 **FontAwesome** – Icons  
- 📦 **Axios** – API calls  
- 📝 **Formik & Yup** – Form handling and validation  
- 🔥 **React Hot Toast** – Toast notifications  
- 🚀 **React Top Loading Bar** – Smooth loading experience  

---

## **Folder Structure** 📁  
```
client/
│── public/               # Static assets
│── src/
│   ├── api/              # API request handling
│   ├── assets/           # Images & icons
│   ├── components/       # Reusable UI components
│   ├── smaller-components/ # Smaller UI components
│   ├── store/            # Redux store & slices
│   ├── App.jsx           # Root component
│   ├── config.js         # Configuration & constants
│   ├── main.jsx          # Entry point
│   ├── index.css         # Global styles
│── .gitignore
│── index.html            # Main HTML file
│── package.json          # Project dependencies
│── vercel.json           # Deployment settings for Vercel
│── vite.config.js        # Vite configuration
```

---

## **Installation & Setup** ⚙️  
### **1. Clone the Repository**  
```sh
git clone https://github.com/subhash1107/docSyncF.git
cd docSyncF
```

### **2. Install Dependencies**  
```sh
npm install
```

### **3. Set Up Environment Variables**  
Create a `.env` file in the root and add your backend URL:  
```
VITE_BACKEND_URL=https://your-backend.onrender.com
```

### **4. Run the Project Locally**  
```sh
npm run dev
```
- Open `http://localhost:5173/` in your browser.

---

## **Deployment** 🚀  
### **Frontend (Vercel)**
This project is deployed on **Vercel**. Ensure the **`vercel.json`** file is configured correctly:

```json
{
  "rewrites": [
    {
      "source": "/(.*)",
      "destination": "/index.html"
    }
  ]
}
```

### **Backend (Render)**
Make sure your backend is running on **Render** and has proper **CORS settings**.

---

## **Contributing** 🤝  
1. Fork the repository  
2. Create a new branch (`git checkout -b feature-branch`)  
3. Commit your changes (`git commit -m "Added new feature"`)  
4. Push to the branch (`git push origin feature-branch`)  
5. Open a **Pull Request**  

---

## **License** 📜  
This project is **open-source** and available under the **MIT License**.

---

This README now includes the **automatic saving feature**! 🚀🔥 Let me know if you need more updates. 😃