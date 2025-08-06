# 📝 Quote Editor (Turbo Rails SPA)

A single-page, reactive quote editor built using **Turbo Rails** — with only **one line of custom JavaScript** for a flash message animation!

This project demonstrates how you can build a highly interactive web application without relying on heavy front-end frameworks like React or Redux. Instead, we take full advantage of **Turbo**, **Stimulus**, and **Ruby on Rails**.

---

## ✨ Features

- 🔁 Reactive UI with Turbo Drive, Turbo Frames, and Turbo Streams
- ➕ Create, Update, and Delete **Quotes**
- 📅 Add and manage **Dates** within each Quote
- 🧾 Add, update, and delete **Line Items** within each Date
- 💰 **Automatic Quote Totals** update in real time when line items change
- ⚡ Minimal custom JavaScript (just a single line!)
- 🧹 Clean and maintainable Rails code with **Simple Form**

---

## 📸 Demo

> **Live Preview:** [Visit the Quote Editor](#)  
(*Link to hosted version if available*)

Create a quote → click on it → add dates → insert line items → watch it update instantly!

---

## 📦 Tech Stack

- **Ruby on Rails** (Turbo-rails enabled)
- **Hotwire (Turbo + Stimulus)**
- **Simple Form**
- **PostgreSQL** (or your preferred DB)
- **Minimal JS** (1 line!)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone git@github.com:Kandarp5268/quote-editor.git
cd quote-editor
```

### 2. Install Dependencies

```bash
bundle install
yarn install # if using Webpacker or jsbundling-rails
```

### 3. Set Up the Database

```bash
rails db:create db:migrate db:seed
```

### 4. Start the Server

```bash
bin/dev
```

> Ensure you have `foreman` or `overmind` installed if using `Procfile`.

---

## 🧪 Run Tests

*(Add test instructions if applicable)*

---

## 🧠 Motivation

This project was inspired by a React-based quote editor I previously built. When [Turbo Rails](https://turbo.hotwired.dev/) launched in December 2020 with the promise:

> “Turbo gives you the speed of a single-page web application without having to write any JavaScript.”

…I wanted to see if it held true.

So I rebuilt the entire editor with Turbo. And yes — it really did live up to the promise:

- ✅ No React  
- ✅ No Redux  
- ✅ No Formik  
- ✅ Just Rails, Turbo, and Simple Form

The result? A fast, reactive, maintainable app with a fraction of the complexity.

---

## 📂 Project Structure

- `app/models` — Quote, Date, LineItem models
- `app/views` — Turbo Frames and Turbo Streams for seamless updates
- `app/controllers` — RESTful Rails controllers
- `app/javascript` — Optional JS for flash messages
- `Procfile.dev` — For parallel JS/CSS/Web server running with `bin/dev`

---

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 👤 Author

**Kandarp Sharma**  
[GitHub](https://github.com/Kandarp-sharma)
