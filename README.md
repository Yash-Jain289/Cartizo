# Cartizo

An E-Commerce application using NodeJS.

# Features

1. ### Authentication of the user with proper validation checks.
2. ### Adding products to the cart.
3. ### Making orders.
4. ### Create, edit and delete a products.
5. ### Pagination to split pages across multiple pages.
6. ### Added a payment method with "Stripe".
7. ### Added an invoice of the orders which is downloadable as a pdf.
8. ### Send a email using "Sendgrid".

# Languages & Tools Used

1. ### NodeJS
2. ### MongoDB
3. ### Mongoose

# Screenshots

![image](https://user-images.githubusercontent.com/67829453/86513469-2f509180-be28-11ea-92ee-dc2864910252.png)
![image](https://user-images.githubusercontent.com/67829453/86513502-63c44d80-be28-11ea-9d23-62cb25f665d6.png)
![image](https://user-images.githubusercontent.com/67829453/86513522-85bdd000-be28-11ea-913d-e11307ce4540.png)
![image](https://user-images.githubusercontent.com/67829453/86513539-979f7300-be28-11ea-97b3-c385a77ecd76.png)

# Setup

To run the project go to the terminal 

```
npm start
```

Install all the dependencies needed to run the project

```
npm install --save-dev nodemon
npm install --save bcryptjs body-parser connect-flash connect-mongodb-session csurf ejs express express-session express-validator mongodb mongoose multer nodemailer nodemailer-sendgrid-transport pdfkit stripe
```

I have used Mongodb Atlas for database storage

See the below link to setup Atlas

<a href="https://docs.atlas.mongodb.com/getting-started/">Click Here</a>

# Documentation

<a href="https://nodejs.org/en/docs/">Nodejs Docs</a><br/>
<a href="https://mongoosejs.com/docs/api.html/">Mongoose Docs</a><br/>
<a href="https://docs.mongodb.com/">Mongodb Docs</a><br/>
<a href="https://stripe.com/docs">Stripe Docs</a><br/>
<a href="https://pdfkit.org/docs/getting_started.html">PDFKit Docs</a><br/>
<a href="https://sendgrid.com/docs/">Sendgrid Docs</a><br/>

