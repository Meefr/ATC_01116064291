# EventHub - ATC_01116064291

**EventHub** is a complete event management solution featuring a **React frontend** and **Node.js backend API**.  
The platform enables users to discover, book, and manage events, while organizers and admins can manage listings, bookings, and users through an intuitive dashboard.

---

## 🚀 Live Demo

👉 [**EventHub Website**](https://meefr.github.io/eventhub-website/)  
✅ Fully functional using the deployed backend and frontend.

---

## 🛠 Technologies Used

- **Frontend**: React, React Router, Axios
- **Backend**: Node.js, Express, MongoDB
- **Other Tools**: Cloudinary, GitHub Pages, Vercel

---

## 📦 Deployment

- **Frontend**: Deployed using [GitHub Pages](https://meefr.github.io/eventhub-website/)
- **Backend**: Deployed via [Vercel](https://vercel.com)

---

## ⚙️ Local Installation

Clone the main repository:

```bash
git clone https://github.com/Meefr/ATC_01116064291.git
```

## 🔁 Backend Setup
### 📁 Check the backend repo for more details: [EventHub-API](https://github.com/Meefr/EventHub-API)

``` bash
cd EventHub-Backend
npm install
```
### 📝 Create a .env file with:
```env
PORT=5000
NODE_ENV=development
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.jgkzg7o.mongodb.net/cluster0?retryWrites=true&w=majority
CLIENT_URL=https://meefr.github.io

CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```
### ▶️ Start the backend:

```bash
npm run dev
```
## 🌐 Frontend Setup
### 📁 Check the frontend repo: eventhub-website

```bash
cd EventHub-Frontend
npm install
npm run dev
```
### 🌍 Visit: http://localhost:5173

## 🔄 Switching Backend (Local/Deployed)
### By default, the frontend uses the local backend. To use the deployed backend:

### 1. Open:

```arduino
./EventHub-Frontend/src/config/index.js
```
### 2. Replace contents with:
```javascript
export const API_BASE_URL = "https://event-hub-api-iota.vercel.app/api/v1";
// export const API_BASE_URL = "http://localhost:5000/api/v1";

export const LANGUAGES = {
  en: "English",
  ar: "العربية"
};
```

### ✅ You can now test your frontend with the deployed backend 🫡

## 📸 Screenshots (Optional)
<iframe src="https://meefr.github.io/eventhub-website/" width="100%" height="500px"></iframe>


## 🤝 Contributions
### Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📄 License
### MIT License — feel free to use and modify!