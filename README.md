---

# **Project Name: Airbnb MERN App**

The **Airbnb MERN App** is a full-stack application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This app allows users to book and list properties, providing functionalities similar to Airbnb, such as user authentication, property listing management, and booking capabilities.

---

## **Mission and Objectives**

### **Mission**
To create a scalable and user-friendly booking platform that connects hosts and guests, enabling seamless property management and reservations.

### **Objectives**
1. Implement a robust property booking and listing system.
2. Provide secure user authentication and authorization.
3. Enable users to manage property details, availability, and bookings.
4. Integrate map functionalities for location-based property searches.
5. Deploy the application for global accessibility.

---

## **Technology Stack**

### **Frontend**
1. **React.js**
   - **Why?** Simplifies UI development with reusable components.
   - **Use Case:** Building the user interface for listing and booking properties.

2. **React Router**
   - **Why?** Enables smooth navigation between pages.
   - **Use Case:** Managing routes such as login, listings, and booking pages.

3. **Tailwind CSS**
   - **Why?** Provides utility-first styling for rapid UI development.
   - **Use Case:** Styling forms, buttons, and layout components.

---

### **Backend**
1. **Node.js**
   - **Why?** Provides a scalable runtime environment for server-side operations.
   - **Use Case:** Handling API requests and server-side logic.

2. **Express.js**
   - **Why?** Simplifies the creation of RESTful APIs.
   - **Use Case:** Creating endpoints for user authentication, property management, and bookings.

3. **JWT (JSON Web Tokens)**
   - **Why?** Ensures secure user authentication.
   - **Use Case:** Managing user sessions.

4. **Multer**
   - **Why?** Handles file uploads, such as property images.
   - **Use Case:** Enabling users to upload photos of their properties.

---

### **Database**
1. **MongoDB**
   - **Why?** Provides a flexible schema for storing user, property, and booking data.
   - **Use Case:** Storing and retrieving property details, user profiles, and booking records.

2. **Mongoose**
   - **Why?** Simplifies MongoDB operations.
   - **Use Case:** Defining schemas and handling database queries.

---

### **Deployment**
1. **Netlify/Vercel**
   - **Why?** Provides fast and reliable hosting for frontend applications.
   - **Use Case:** Hosting the React application.

2. **Render/Heroku**
   - **Why?** Ensures scalable backend hosting.
   - **Use Case:** Deploying APIs and database connections.

---

## **System Architecture**
The app follows a standard MERN architecture:
1. **Frontend:** React communicates with the backend via RESTful APIs.
2. **Backend:** Express handles requests, performs server-side logic, and interacts with MongoDB.
3. **Database:** MongoDB stores user, property, and booking details.
4. **Authentication:** JWT manages user sessions and access control.

---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

## **Week-by-Week Learning Plan**

### **Week 1: Project Setup and Basic UI**
- **Goal:** Set up the foundational structure for the Airbnb MERN App.
- **Tasks:**
  1. Initialize React and Node.js projects.
     - **Reading:** [Setting Up MERN Stack](https://www.mongodb.com/mern-stack)
     - **Video:** [MERN Stack Crash Course](https://www.youtube.com/watch?v=fnpmR6Q5lEc)
  2. Create the project directory structure.
     - **Reading:** [React App Structure](https://react.dev/blog/2023/03/16/introducing-react-dev)
     - **Video:** [React Basics](https://www.youtube.com/watch?v=SqcY0GlETPk)
  3. Set up Tailwind CSS for styling.
     - **Reading:** [Tailwind CSS Docs](https://tailwindcss.com/docs/installation)
     - **Video:** [Tailwind CSS Setup](https://www.youtube.com/watch?v=UBOj6rqRUME)

- **Deliverables:**
  - Basic project setup with initial UI components.

---

### **Week 2: User Authentication**
- **Goal:** Implement secure user authentication and session management.
- **Tasks:**
  1. Create user schema in MongoDB.
     - **Reading:** [MongoDB Schema Design](https://mongoosejs.com/docs/guide.html)
     - **Video:** [Mongoose Models](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  2. Build authentication APIs with JWT.
     - **Reading:** [JWT Basics](https://jwt.io/introduction/)
     - **Video:** [JWT Implementation Guide](https://www.youtube.com/watch?v=mbsmsi7l3r4)
  3. Create login and signup pages in React.
     - **Reading:** [React Forms](https://react.dev/blog/2023/03/16/introducing-react-dev)
     - **Video:** [Building Forms in React](https://www.youtube.com/watch?v=SdzMBWT2CDQ)

- **Deliverables:**
  - Functional login and signup system.

---

### **Week 3: Property Management**
- **Goal:** Enable users to list and manage properties.
- **Tasks:**
  1. Design property schema in MongoDB.
     - **Reading:** [MongoDB Schema Guide](https://www.mongodb.com/docs/manual/data-modeling/)
     - **Video:** [Mongoose Models](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  2. Build APIs for property CRUD operations.
     - **Reading:** [RESTful API Design](https://restfulapi.net/)
     - **Video:** [Building REST APIs](https://www.youtube.com/watch?v=pKd0Rpw7O48)
  3. Create property management UI in React.
     - **Reading:** [Material-UI Components](https://mui.com/getting-started/usage/)
     - **Video:** [React Form Handling](https://www.youtube.com/watch?v=neHpLIKPp5M)

- **Deliverables:**
  - Property listing and management functionality.

---

### **Week 4: Booking System**
- **Goal:** Implement a booking system for users to reserve properties.
- **Tasks:**
  1. Design booking schema in MongoDB.
     - **Reading:** [MongoDB Schema Guide](https://www.mongodb.com/docs/manual/data-modeling/)
     - **Video:** [Mongoose Models](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  2. Build booking APIs.
     - **Reading:** [RESTful API Design](https://restfulapi.net/)
     - **Video:** [Building REST APIs](https://www.youtube.com/watch?v=pKd0Rpw7O48)
  3. Create booking management UI in React.
     - **Reading:** [React State Management](https://react.dev/blog/2023/03/16/introducing-react-dev)
     - **Video:** [React State Tutorial](https://www.youtube.com/watch?v=35lXWvCuM8o)

- **Deliverables:**
  - Fully functional booking system.

---

### **Week 5: Map Integration and Deployment**
- **Goal:** Add map functionalities and deploy the application.
- **Tasks:**
  1. Integrate Google Maps API for property locations.
     - **Reading:** [Google Maps API Docs](https://developers.google.com/maps/documentation)
     - **Video:** [Google Maps in React](https://www.youtube.com/watch?v=WZcxJGmLbSo)
  2. Deploy the frontend on Netlify or Vercel.
     - **Reading:** [Netlify Deployment Guide](https://docs.netlify.com/)
     - **Video:** [Deploying React Apps](https://www.youtube.com/watch?v=YdYyYMFPa44)
  3. Deploy the backend on Render or Heroku.
     - **Reading:** [Render Deployment Guide](https://render.com/docs)
     - **Video:** [Node.js Deployment Tutorial](https://www.youtube.com/watch?v=l134cBAJCuc)

- **Deliverables:**
  - Fully deployed Airbnb MERN App.

---

## Screenshots
![Screenshot (359)](https://github.com/user-attachments/assets/3f818eab-363e-42bf-a7d3-be2ac3f2529a)
![Screenshot (354)](https://github.com/user-attachments/assets/84c43e25-0b13-4fe4-9dd3-6ea862984d39)
![Screenshot (355)](https://github.com/user-attachments/assets/03b03bf4-a6df-45da-92f1-ca1f2764aa9d)
![Screenshot (356)](https://github.com/user-attachments/assets/7ebc1520-0cea-4b2d-aa0f-c525aaacd820)
![Screenshot (357)](https://github.com/user-attachments/assets/623ad3be-6a19-40d8-a747-a7eee629da91)
![Screenshot (358)](https://github.com/user-attachments/assets/295be159-4b7b-44c8-9370-f6666a518ec9)


---
## **References**
1. [React Documentation](https://react.dev/blog/2023/03/16/introducing-react-dev)
2. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
3. [Material-UI Documentation](https://mui.com/)
4. [Google Maps API Documentation](https://developers.google.com/maps/documentation)
5. https://github.com/dejwid/airbnb-clone
6. https://www.youtube.com/watch?v=MpQbwtSiZ7E

