# Project - Mern-Bookstore

### Project Initialization :-

1) Installed **mongoose, dotenv, express and nodemon** through npm.
   * `npm install mongoose dotenv express nodemon`
   
   (note that you can also use `npm i` as a shorthand for `npm install`

2) Initialized an **npm project** after creating two directories named **backend** and **frontend**.
   * `npm init -y`

3) Inside backend, created **src** directory and inside it created a **server.js** file.

4) Updated the **main** and **scripts** attributes of **package.json** to start and run the server at `src/server.js`.
   * `"start": "node src/server.js"`
   * `"dev": "nodemon src/server.js"`

5) Created an **express server** and made it listen to port stored in **.env (3000)** or **3001**.

6) Created **config, controllers, models, routes** directories and respective files inside the **src** folder.

---

### Mongo DB setup :-

1) Signed up from a own **google account** on **MongoDB Atlas**.

2) Created a **free cluster** and set it up with **nodejs driver**.

3) In **DB.js**, we wrote basic `mongoose.connect()` code in a **try-catch block**. If successful, then we log, "MongoDB connected successfully" and in catch we catch all errors and log the error and **exit the process with 1**.

4) We write the **Book schema** inside the `bookModel.js`. The schema is followed as:

**bookSchema**
* **title**: `{type: String, required: true}`
* **author**: `{type: String, required: true}`
* **publishYear**: `{type: String, required: true}`
* `{timestamps: true}`

5) Sorting in MongoDB :-
* `{attribute : 1}` ascending
* `{attribute : -1}` descending

---
