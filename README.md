# 🍽️ Restro – Food Explorer Website

**Restro** is a simple and responsive restaurant website that allows users to explore different food items based on categories such as Breakfast, Dessert, Pasta, Seafood, Vegetarian, and Starter.

The website uses the **TheMealDB API** to fetch real-time meal data and displays the results dynamically using Bootstrap cards.

## 🚀 Features

* 🔍 Search food items by category
* 🍳 Breakfast menu
* 🍰 Dessert menu
* 🍝 Pasta menu
* 🦐 Seafood menu
* 🥗 Vegetarian menu
* 🍽️ Starter menu
* 🖼️ Dynamic food images
* 📝 Displays meal names dynamically
* 🛒 Buy Now button for each food item
* 📱 Responsive layout using Bootstrap
* 🌐 Fetches food data from an external API

## 🛠️ Technologies Used

* **HTML5** – Used to create the structure of the website
* **Bootstrap 5** – Used for responsive design and UI components
* **JavaScript** – Used to fetch API data and dynamically display meals
* **TheMealDB API** – Used to retrieve meal information and images

## 🔗 API Used

This project uses the **TheMealDB API** to retrieve food data.

The API endpoint used in the project is:

```text
https://www.themealdb.com/api/json/v1/1/filter.php?c={category}
```

For example, selecting `Breakfast` sends a request for breakfast meals.

## 📂 Project Structure

```text
Restro/
│
├── index.html
└── README.md
```

## ⚙️ How It Works

1. The user selects a food category from the dropdown menu.
2. The user clicks the **Search** button.
3. JavaScript gets the selected category using `getElementById()`.
4. The `fetch()` function sends a request to TheMealDB API.
5. The API returns meal data in JSON format.
6. JavaScript processes the returned data.
7. Bootstrap cards are dynamically generated for each meal.
8. The meals are displayed inside the results section.

## 💻 JavaScript Concepts Used

This project demonstrates several important JavaScript concepts:

* Functions
* DOM manipulation
* `getElementById()`
* `fetch()` API
* Promises
* `.then()`
* JSON data
* Arrays
* Loops
* Template literals
* `innerHTML`
* Event handling with `onclick`

## 🎨 Bootstrap Components Used

The project uses Bootstrap 5 classes including:

* `container`
* `row`
* `col-md-9`
* `col-md-3`
* `col-md-4`
* `form-select`
* `btn`
* `btn-success`
* `btn-warning`
* `card`
* `card-img-top`
* `card-body`
* `text-center`

These classes make the website responsive and reduce the amount of custom CSS required.

## 📱 Responsive Design

The website uses Bootstrap's grid system to adapt the layout to different screen sizes.

On medium and larger screens, food cards are displayed in multiple columns, while Bootstrap automatically adjusts the layout on smaller devices.

## 🔮 Future Improvements

The project can be improved by adding:

* 🛒 Functional shopping cart
* 💰 Food prices
* 🔢 Quantity selection
* ❤️ Favorite meals
* 📄 Detailed meal information
* 🔐 User authentication
* 💳 Online payment
* 📦 Order management
* 🔎 Search by meal name
* ⭐ Food ratings and reviews
* 🎨 Improved restaurant-themed UI

## 📌 Note

The current **Buy Now** button is only a demonstration button. It does not currently add an item to a shopping cart or process an order.

## 👨‍💻 Author

**Ayush Jha**

This project was created as a frontend development practice project using HTML, Bootstrap, JavaScript, and a public food API.

---

⭐ **If you like this project, don't forget to give the repository a star!**
