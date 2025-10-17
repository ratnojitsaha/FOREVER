<div align="center">

  # FOREVER 🛒
</div>

**FOREVER** is a full-stack web application that enables users to explore a variety of products, filter them based on specific attributes, and add items to their cart by selecting desired variants like size. Users can place orders by providing delivery addresses and selecting their preferred payment method—either **Cash on Delivery (COD)** or **Online Payment**. The application integrates `Stripe` as the online payment gateway, ensuring secure and seamless transactions.

Additionally, an **Admin Dashboard** is included, where administrators can manage the store by uploading new products, deleting existing ones, and viewing all products listed in the store.

<br/><hr/><br/>

<div align="center">

## DEMO 🌐
  
**UI** Live 👉 [LINK](live link)

**Admin Dashboard** 👉 [LINK](admin dashboard link)
</div>

<br/><hr/><br/>

<div align="center">
  
# Table of Contents 📜

[Key-Features](#key-features)

[Technologies-Used](#technologies-used)

[Installation-and-Setup](#installation-and-setup)

[Future-Enhancements](#future-enhancements)

[Contribution](#contribution)

[License](#license)

</div>

<br/><hr/><br/>

## Key-Features
### For Users:
* **Product Exploration**: Browse a variety of products and filter them by category, size, and other attributes.
* **Cart Management**: Add, view, and modify products in the cart.
* **Order Placement**: Provide delivery addresses and select payment methods (COD or online payment via Stripe).
* **Secure Payments**: Stripe integration for secure online payments.

### For Admins:
* **Product Management**: Add, edit, or delete products.
* **Order Monitoring**: View orders placed by users.
* **Inventory Overview**: Access all products listed in the store.

<br/><hr/><br/>

## Technologies-Used
This project is built using the `MERN Stack` (MongoDB, Express.js, React.js, and Node.js), ensuring a robust, scalable, and modern web application.

* **Frontend**: React.js for building a responsive and interactive user interface.
* **Backend**: Node.js and Express.js for API development.
* **Database**: MongoDB for storing user, product, and order data.
* **Payment Gateway**: Stripe for secure online transactions.

<br/><hr/><br/>

## Installation-and-Setup
1. Clone the repository:

```console
git clone https://github.com/elyse502/ecommerce-app.git
cd ecommerce-app
```

2. Install dependencies for both client and server:

```console
cd backend
npm install

cd frontend
npm install

cd admin
npm install
```

3. Create an `.env` file in the root directory for server-side configuration and add the following:

```console
MONGO_URI="your_mongodb_connection_string"
CLOUDINARY_API_KEY="your_cloudinary_api_key"
CLOUDINARY_SECRET_KEY="your_cloudinary_secret_key"
CLOUDINARY_NAME="your_cloudinary_name"
JWT_SECRET="your_jwt_secret_key"
ADMIN_EMAIL="admin_email_address"
ADMIN_PASSWORD="admin_password"
STRIPE_SECRET_KEY="your_stripe_secret_key"
```

4. Start the development server:

* Back-End
```console
npm run server
```
* Front-End
```console
npm run dev
```
* Admin
```console
npm run dev
```

5. Access the app on `http://localhost:5173/` for **UI** and `http://localhost:5174/` for **Admin Panel**.

<br/><hr/><br/>


## Future-Enhancements
* Add product reviews and ratings.
* Implement user authentication with social logins.
* Add a _"Wishlist"_ feature for users to save products for future reference.

<br/><hr/><br/>

## Contribution
Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request with your updates or fixes.

<br/><hr/><br/>

## License
This project is licensed under the MIT License. See the LICENSE ➡️ [file](https://github.com/https://github.com/ratnojitsaha/FOREVER/blob/main/LICENSE) for more details📃.

<br /><hr /><br />

## Author :black_nib:
[Github](https://github.com/ratnojitsaha) | [Linkedin](https://www.linkedin.com/in/saharatnojit/) | [Twitter](https://x.com/steelshot04)._



[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/niyibizi-elys%C3%A9e/) [![@phenrysay](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Niyibizi_Elyse) [![pH-7](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elyse502)

<br />




