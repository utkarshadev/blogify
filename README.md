# Blogify

Blogify is a simple blogging platform built with Node.js, Express, MongoDB, and EJS. Users can sign up, sign in, create blogs, comment, and upload images.

## Features

- User authentication (signup, signin, logout)
- Create, view, and comment on blog posts
- Image upload for blog cover images
- Responsive UI with Bootstrap

## Project Structure

- `app.js` – Main Express app
- `models/` – Mongoose models (`user.js`, `blog.js`, `comment.js`)
- `routes/` – Express routes (`user.js`, `blog.js`)
- `middlewares/` – Authentication middleware
- `services/` – JWT authentication service
- `views/` – EJS templates
- `public/` – Static files (images, uploads)

## Setup

1. **Install dependencies:**
   ```sh
   npm install
   ```

2. **Configure environment:**
   - Set MongoDB connection string in `.env`:
     ```
     MONGO_URL=mongodb://localhost:27017/blogify
     ```

3. **Run the app:**
   ```sh
   npm run dev
   ```
   or
   ```sh
   npm start
   ```

4. **Access the app:**
   - Visit [http://localhost:8000](http://localhost:8000)

## Usage

- Sign up for a new account
- Sign in to create blogs and comment
- Upload images for blog posts

## License

ISC

---

See [app.js](app.js), [routes/user.js](routes/user.js), [routes/blog.js](routes/blog.js), and [models/user.js](models/user.js) for implementation