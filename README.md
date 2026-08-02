# BookShoppingCartMvc

BookShoppingCartMvc is a simple e-commerce application built with **ASP.NET Core MVC**. It was created to help beginners understand how an online shopping cart works and has been expanded into a basic online bookstore.

The application allows users to browse books, add them to a shopping cart, place orders, and view their order history. It also includes an admin panel to manage books, genres, stock, and customer orders.

This project is intended for learning and practicing ASP.NET Core MVC concepts. It does not include an online payment gateway and currently supports **Cash on Delivery (COD)** only.

If you find this project useful, consider giving it a **Star** on GitHub.
```

## Tech stack 

   - Dotnet core mvc (.Net 9)
   - MS SQLServer 2022 (Database)
   - Entity Framework Core (ORM)
   - Identity Core (Authentication)
   - Bootstrap 5 (frontend)

## Tools I have used and their alternative

- Visual Studio 2022 (Alternatives (.NET SDK + VS Code or .NET SDK + JetBrains Rider)
- Microsoft Sql Server Management Studio (Alternative Azure data studio or you can just execute sql from terminal)


## How to run the project?

1. Open the command prompt. Go to a directory where you want to clone this project. Use this command to clone the project.

```bash
git clone https://github.com/rd003/BookShoppingCart-Mvc
```

2. Go to the directory where you have cloned this project, open the directory `BookShoppingCart-Mvc`. You will find a file with name `BookShoppingCartMvc.sln`. Double click on this file and this project will be opened in Visual Studio.

3. Open `appsettings.json` file and update connection string.

```json
"ConnectionStrings": {
  "conn": "data source=your_server_name;initial catalog=MovieStoreMvc; integrated security=true;encrypt=false"
}
```

4. Run the project.

 When you run the project for the first time, it will do following things:

- It will generate the database
- It will seed some data
- It will create an account for `admin`

## How to logged-in with admin account?? 

Click on the link named `login` and get logged-in with these credentials.

```text
username: admin@gmail.com

password: Admin@123
```

## Screenshots

1.Homepage

![homepage](./screenshots/1.jpg)

2.Homepage continued

![homepage2](./screenshots/2.jpg)

3.Login

![login](./screenshots/3.jpg)

4.Registration

![registration](./screenshots/4.jpg)

5.Add To Cart

![add-to-cart](./screenshots/5.jpg)

6.Cart

![cart](./screenshots/6.jpg)

7.Checkout

![cart](./screenshots/7.jpg)

8.Order success

![order_suceess](./screenshots/8_order_success.jpg)

9.Admin Login

![Admin Login](./screenshots/9_admin_login.jpg)

10.Admin Dashboard

![Admin Dashboard](./screenshots/10%20admin%20dashboard.jpg)

11.Orders

![Orders](./screenshots/11%20admin%20orders.jpg)

12.Order Detail

![Order Detail](./screenshots/12%20admin%20order%20detail.jpg)

13.Update Order Status

![Update Order Status](./screenshots/13%20Update%20Order%20Status.jpg)

14.Display Stock

![Display Stock](./screenshots/14%20%20display%20stock.jpg)

15.Update Stock

![Update Stock](./screenshots/15%20update%20stock.jpg)

16.Display Genre

![Display Genre](./screenshots/16%20display%20genres.jpg)

17.Add Genre

![Add Genre](./screenshots/17%20add%20genre.jpg)

18.Update Genre

![Update Genre](./screenshots/18%20Update%20Genre.jpg)

19.Display Books

![Display Books](./screenshots/19%20display%20books.jpg)

20.Add Book

![Add Book](./screenshots/20%20add%20books.jpg)

21.Update Book

![Update Book](./screenshots/21%20update%20book.jpg)

22.Top Selling Books

![Top Selling Books](./screenshots/22%20top%20selling%20books.jpg)

## Thanks
