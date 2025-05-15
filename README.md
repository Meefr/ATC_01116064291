# ATC_01116064291 - EventHub Website

## Description
EventHub is a complete event management solution featuring a React frontend and Node.js backend API. The platform enables users to discover, book, and manage events, while organizers and administrators can handle event listings, user management, and bookings through an intuitive dashboard.
## Deployment

Project is already deployed

- Frontend is deployed using `github pages`
- Backend is deployed using `vercel`

## Demo

Link : [EventHub](https://meefr.github.io/eventhub-website/) `this is full functional website the use deployed version of backend and frontend`

## Instlation for local run

- `git clone https://github.com/Meefr/ATC_01116064291.git`
- ### Backend: 
    #### Check [GitHub Repo](https://github.com/Meefr/EventHub-API) for more details
    - `cd EventHub-Backend`
    - `npm i`
    - Setup .env file
        ``` PORT=5000
        NODE_ENV=development
        MONGO_URI=mongodb+srv://<username>:<password>@cluster0.jgkzg7o.mongodb.net/cluster0?retryWrites=true&w=majority
        <!-- If you run website locak no need for this  -->
        CLIENT_URL=https://meefr.github.io

        CLOUDINARY_NAME=your_cloudinary_name
        CLOUDINARY_API_KEY=your_cloudinary_api_key
        CLOUDINARY_API_SECRET=your_cloudinary_api_secret
        ```
    - `npm run dev`
- ### FrontEnd:
    #### Check [GitHub Repo](https://github.com/Meefr/eventhub-website) for more details
    - `cd EventHub-Frontend`
    - `npm i`
    - `npm run dev`
    - `visit http://localhost:5173`

- Note `Fronend use local backend by defult if you want to change it follow this steps`
    - Go to `./EventHub-Frontend/src/config/index.js`
    - Update this file to be
        ``` javascript
        export const API_BASE_URL = "https://event-hub-api-iota.vercel.app/api/v1";
        // export const API_BASE_URL = "http://localhost:5000/api/v1";

        export const LANGUAGES = {
        en: "English",
        ar: "العربية"
        };
        ``` 
    - Now you test  your frontend using the deployed version of backend 🫡


