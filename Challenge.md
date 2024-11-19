# Full-stack Challenge Guide

The Full-stack Challenge encourages you to create a CRUD (Create, Read, Update, Delete) web application that showcases your skills in both backend and frontend development. We will assess your ability to use modern frameworks and tools while emphasizing clean, maintainable code and a polished, user-friendly product.

### **Technology Stack Overview**
This project requires using the following technologies:

### Backend: **Hono, Node.js, TypeScript, PostgreSQL**
- **Hono** is a minimal and fast web framework designed for performance and simplicity. It allows you to build fast, scalable APIs while maintaining a clean and minimal codebase.
- **Node.js** is a popular server-side JavaScript runtime. It allows for fast, asynchronous processing and is great for I/O-intensive applications like web services.
- **TypeScript** adds static types to JavaScript, helping catch errors at compile time and improving code readability and maintainability.
- **PostgreSQL** is a powerful, open-source relational database. It’s highly reliable and supports advanced features like ACID compliance, transactions, and robust querying capabilities.

**Why use these technologies?**
- **Performance**: Hono is designed for performance, and PostgreSQL provides reliable data handling. This stack allows you to build scalable, efficient applications.
- **Maintainability**: TypeScript ensures your code is more robust and less error-prone, which is important for growing projects.
- **Popular and Marketable Stack**: Node.js, TypeScript, and PostgreSQL are widely used in the industry, making them valuable skills for any developer.

### **Frontend: Remix, TypeScript**
- **Remix** is a modern React framework that focuses on fast, dynamic web applications. It provides built-in data loading, caching, and routing to help you build production-ready apps efficiently.
- **TypeScript** ensures type safety in your frontend code, preventing common JavaScript pitfalls and making it easier to maintain and scale your application.

**Why use Remix?**
- **Optimized for Performance**: Remix uses a "fetch as you render" model to make pages load faster and improve the user experience.
- **Data Management**: Remix uses loaders for data fetching on the server side, which simplifies managing state and keeps your frontend code clean.
- **React + Remix = Great UX**: Remix leverages React’s declarative UI and pairs it with strong data handling for a smooth user experience.

---

### **Project Requirements**

#### **Backend**

1. **Hono Server Setup**
   - Set up a basic server with **Hono** in **Node.js** using **TypeScript**.
   - Ensure that your server handles HTTP requests properly (GET, POST, PUT, DELETE).
   - Include basic **authentication** with sign-up and sign-in functionality (JWT, session-based, etc.).

2. **Database Interaction (PostgreSQL)**
   - Connect the server to a **PostgreSQL** database.
   - Implement CRUD operations to create, read, update, and delete records in the database.
   - Ensure proper validation and error handling throughout the CRUD operations.
   - Remember to document your relational schema and ensure migrations handling.

#### **Frontend**

1. **Remix Web App**
   - Set up a **Remix** frontend that interacts with the backend.
   - Implement authentication on the frontend, with sign-up and sign-in pages (JWT or session-based).
   - Create pages for:
     - **Creating** a new record (form-based interaction).
     - **Reading** existing records (display records in a list or table).
     - **Updating** existing records (editable form).
     - **Deleting** existing records (confirmation prompt before deletion).

2. **Data Fetching with Remix Loaders**
   - Use **Remix loaders** for fetching data on the server side and passing it to your components.
   - Ensure that the frontend is responsive and works well across different devices.

---

### **Bonus and Extras**

The following bonuses will help demonstrate your full-stack capabilities and make your submission stand out:

1. **Open Source**:
   - Share your code on GitHub to demonstrate your ability to work in a collaborative, open-source environment.
   - Include a clear README file with instructions on how to run the application, set up the database, and deploy it.

2. **Automated Tests**:
   - Write unit and integration tests for both backend and frontend using **Vitest** and **React Testing Library**.
   - Ensure your tests are comprehensive, covering key parts of the app (authentication, CRUD operations, data fetching).

3. **Design System**:
   - Implement a simple design system using **React Aria** components and **Panda CSS**.
   - Focus on accessibility and user experience. Use pre-built components from React Aria and customize them with Panda CSS for styling.

4. **API Documentation**:
   - Use **OpenAPI** (Swagger) for documenting your backend API endpoints. Provide details on how to authenticate, interact with the API, and what each endpoint does.
   - Optionally, use **[Scalar](https://github.com/scalar/scalar)** for generating amazing✨ API docs.

5. **Deployment**:
   - Deploy both the frontend and backend to a cloud platform (e.g., **Vercel**, **Netlify**, **Heroku**, **AWS**).
   - Ensure that your app is easily accessible, and include any necessary environment variables for production.

6. **CI/CD Pipeline**:
   - Set up a **CI/CD** pipeline using GitHub Actions or another service. This should automatically run tests, build your app, and deploy it upon changes.

---

### **Creativity and Design**

While the technical aspects are crucial, **creativity** in terms of product and **design** will be greatly considered. We encourage you to:

- **Innovate**: Think about unique use cases for the CRUD functionality. For example, consider adding filtering, sorting, or even paginated views for large sets of records.
- **Design a Polished UI**: Pay attention to the aesthetics and usability of your application. Simple UI designs using modern design principles are preferred. A clean, intuitive UI will set your project apart.
- **Think About User Experience**: Ensure that the authentication flow is smooth and intuitive. Consider adding feedback (success/error messages, loading spinners, etc.) where necessary.
  
We’re looking for thoughtful, user-friendly designs that showcase your understanding of both frontend and backend development, as well as your attention to detail.

---

### **How to Get Started?**

1. **Create a new repo for your project**.
2. **Join the [Discord Server](https://discord.gg/vM5fXyUs)**. Our developers are available to assist you. Feel free to ask any questions in the public channels, and we’ll be happy to help!
3. **Start building**! Make sure to frequently commit your code and document your progress.
4. **Share your project** when you’re finished, including the GitHub repository link and live URL (if it is available).

---

### **Useful Resources**

- **[Hono](https://hono.dev/)**  
  A minimal and fast web framework for building APIs with Node.js. It's designed for high performance and simplicity. It is a great idea to follow their docs examples.

- **[Remix](https://remix.run/)**  
  A modern React framework that focuses on optimizing user experience, data loading, and rendering. It allows you to build fast, scalable web apps with built-in routing, caching, and data management. Make sure to read the docs and understand how the [Server Side Rendering](https://remix.run/docs/en/main/discussion/introduction) works.

- **[Zod](https://zod.dev/)**  
  A TypeScript-first schema declaration and validation library. It helps you validate and parse complex data structures in a type-safe manner, which is especially useful for handling form inputs, API responses, and more.

- **[Porsager Postgres](https://github.com/porsager/postgres)**  
  A lightweight, fast PostgreSQL client for Node.js, built to be simple, efficient, and easy to use. It provides a straightforward API to interact with PostgreSQL from your Node.js backend.

- **[Panda CSS](https://panda-css.com/)**  
  A utility-first CSS framework that provides a modern approach to styling web applications. It combines powerful design tokens with easy-to-use utility classes to build responsive and scalable UIs quickly.

- **[Bem-te-vi Dev.to](https://dev.to/bem-te-vi)**  
  bem-te-vi's technical blog.

- **[Swagger - OpenAPI Documentation](https://swagger.io/docs/specification/v3_0/about/)**  
  Swagger provides a framework for defining, documenting, and consuming RESTful APIs. The OpenAPI Specification (OAS) is widely used for creating interactive API documentation and generating client SDKs.

---

We look forward to seeing your project, and remember: **creativity counts**.
