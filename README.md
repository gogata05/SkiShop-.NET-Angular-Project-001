Ski_Shop-.NET-Angular-Project-001

# Ski_Shop

## Introduction

This project is a full-stack application built with .NET on the backend and Angular on the frontend. It serves as an e-commerce platform with features like user authentication, product browsing, and an integrated shopping cart.

## Features

- .NET REST API
- Angular
- TypeScript
- Stripe Payment and Discounts
- Filters, Sorting, Pagination
- Roles

## How to use?

- 0.Download the repository, extract it to folder and open with Visual Studio Code

Open Terminal in "API" folder:

- 1.Add appsetting.json with:

```
{
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Information"
    }
  },
  "StripeSettings": {
    "PublishableKey": "Your PublishableKey",
    "SecretKey": "Your SecretKey",
    "WhSecret": "Your WhSecret"
  },
  "AllowedHosts": "*"
}
```

- 2.dotnet run

Open Terminal in "client" folder:

- 1.npm install
- 2.ng serve
- 3.Start on: https://localhost:4200/

## Photos

1. **Dashboard**
   ![Dashboard](API/wwwroot/images/photos/1Dashboard.png)

2. **Cart**
   ![Cart](API/wwwroot/images/photos/2Cart.png)

3. **Order Step 1 - Add Address**
   ![Order Step 1 - Add Address](API/wwwroot/images/photos/3Order%20Step%201%20-%20Add%20Address.png)

4. **Order Step 2 - Shipping Type**
   ![Order Step 2 - Shipping Type](/API/wwwroot/images/photos/4Order%20Step%202%20-%20Shipping%20Type.png)

5. **Order Step 3 - Stripe Payment**
   ![Order Step 3 - Stripe Payment](/API/wwwroot/images/photos/5Order%20Step%203%20-%20Stripe%20Payment.png)

6. **Order Step 4 - Confirmation**
   ![Order Step 4 - Confirmation](/API/wwwroot/images/photos/6Order%20Step%204%20-%20Confirmation.png)

7. **Discount**
   ![Discount](/API/wwwroot/images/photos/7Discount.png)

8. **Product Details**
   ![Product Details](/API/wwwroot/images/photos/9Product%20Details.png)

9. **Filters**
   ![Filters](/API/wwwroot/images/photos/10Filters.png)

10. **Sorting 1**
    ![Sorting 1](/API/wwwroot/images/photos/11Sorting1.png)

11. **Sorting 2**
    ![Sorting 2](/API/wwwroot/images/photos/12Sorting2.png)

12. **Dropdown**
    ![Dropdown](/API/wwwroot/images/photos/13Dropdown.png)

13. **Home**
    ![Home](/API/wwwroot/images/photos/14Home.png)

14. **Login**
    ![Login](/API/wwwroot/images/photos/15Login.png)

15. **Register**
    ![Register](/API/wwwroot/images/photos/16Register.png)

16. **Order Confirmation**
    ![Order Confirmation](/API/wwwroot/images/photos/17Order%20Confirmation.png)

17. **Orders**
    ![Orders](/API/wwwroot/images/photos/18Orders.png)

18. **Order Details**
    ![Order Details](/API/wwwroot/images/photos/19Order%20Details.png)
