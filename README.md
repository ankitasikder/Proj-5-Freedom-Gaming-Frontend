# FREEDOM-GAMING-ECOMMERCE-APPLICATION-FRONTEND :star_struck: 

***This new e-commerce application named 'FREEDOM GAMING' is created by Ankita Sikder and other Group members for project 5, students of BTECH, in University of Engineering and Management, Kolkata.***

**Email Id: ankita.sikder14@gmail.com.** 

[![Generic badge](https://img.shields.io/badge/react--native-community-brightgreen)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/react-navigation-yellow)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/axios-%5E0.21.0-important)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/expo-~39.0.2-yellowgreen)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/expo--image--picker-~9.2.1-maroon)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/expo--status--bar-~1.0.2-red)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/jwt--decode-%5E3.1.2-blueviolet)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/mime-%5E2.6.0-brightgreen)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/native--base-%5E2.13.14-blue)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/react-16.13.1-ff69b4)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/react--native--gesture--handler-%5E1.7.0-purple)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/react--native--reanimated-%5E1.13.3-9cf)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/react--native--screens-%5E2.10.1-red)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/redux-%5E4.1.0-yellow)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/styled--components-%5E5.2.1-blue)](https://shields.io/) 

## About :point_down: 

<div align="justified">
       
This is an e-commerce electronics and gaming items shopping application for android and ios. Its a ecommerce application using react native. React Native (also known as RN) is a popular JavaScript-based mobile app framework that allows you to build natively-rendered mobile apps for iOS and Android. Here is register or login option when user opens for the first time. Here user has to register for the first time using email id, phone number, username and password. After the firt time user has to login with email id and password. Here is also a sigh out option for security purpose. In this shopping app there is a search engine where user can search products by name, company or categories. These search engine is made for making it user-friendly. Here are total 26 categories and 251 products in specific quantities. We can check products by choosing different categories. In each product there is a slider of images of that product and detailed description of that product including quantity, company name, availability status, price. Here is an Add button to add that product in cart. In the cart we can find tha product. Later we can easily order that item. There are two buttons here. Clear button is used for clearing the cart. If we want to order that product we have to proceed with Checkout button. There are 3 steps for ordering SHIPPING, PAYMENT and CONFIRM. In the Shipping Address part we have to give proper phone number, shipping address 1 and 2, city and a zip code for security. Here is also a drop down menu for choosing the country name. In the next part we can choose payment method among Cash on Delivery, Bank Transfer and Card Payment. After that we can proceed with CONFIRM button. In the final step we can place order. We can see our order in account section. Here we can see all detrails regarding our order. We can check the status of that order. For admin users there are additionl options. In the settings option user can use dd products option to dd poduct in ny ctegories. Here user has to write brand, name, price, count in stock, description for that product. User can also use camera to take images of that product from phone's internal storage. In the dd categories button user can add categoies by giving names. Here user can also delete an existing category. In the orders section user can see all orders of daily deals and also will be able to change the status of that order. Here user can choose among pending, shipped, delivered and update the status. This is a user-friendly android e-commerce shopping application.
       
</div>

## Backend Link :point_right: 
https://freedom-gaming-ipa.herokuapp.com/api/v1/

## Github Link of Backend :point_right: 
       
## APP DOWNLOAD LINK : :point_right: <a href="https://drive.google.com/file/d/1F91JgwaQmm6BjiWpNn2dBl-h8HRl6icx/view" download>Click here to download</a>

## Folder Structure :point_down:

```bash
Screens
   ├── admin
   |     ├── categories.js
   |     ├── listItem.js
   |     ├── Orders.js
   |     ├── ProductForm.js
   |     └── Products.js
   ├── Screens
   |     ├── CHECKOUT_OF_OD
   |     |      ├── CheckoutforDD.js
   |     |      ├── Confirm.js
   |     |      └── PaymentForDD.js
   |     ├── Cart.js
   |     └── CartItem.js
   ├── Products
   |     ├── CategoryFilter.js
   |     ├── ProductCard.js
   |     ├── ProductContainer.js
   |     ├── ProductList.js
   |     ├── SearchedProducts.js
   |     └── SingleProduct.js
   └── user
         ├── login.js
         ├── Register.js
         └── SingleProfile.js
```                      
This part is created with javascript for different screens.
```bash
Navigators
    ├── AdminNavigator.js
    ├── CheckoutNavigator.js
    ├── HomeNavigator.js
    ├── CastNavigator.js
    └── userStackNavigator.js
```
This part is created with javascript for navigations.
```bash
ContextApi
   ├── Actions
   |     └── Auth.actions.js
   ├── Reducers
   |     └── Auth.reducer.js
   └── Store
         ├── Auth.js
         └── AuthGlobal.js  
```
This part is created with javascript for authentication.
```bash
ReduxDev
   ├── Actions
   |     └── CartActionsForDD.js
   ├── ReducersForDD
   |     └── CartItem.js
   ├── StoreForDD
   └── Constants.js
```
<a href="pics/Redux.gif"><img src="pics/Redux.gif" width="800" height= "300"></a>
```bash
Shared
   ├── Form
   |     ├── FormContainer.js
   |     └── Input.js
   ├── StyledComponents
   |     ├── EasyButton.js
   |     └── Trafficlight.js
   ├── Banner.js
   ├── CartIcon.js
   ├── Error.js
   ├── Header.js
   └── OrderCardDD.js
```
This part is created with javascript for different styles.
```bash
assets
   ├── Common
   |     ├── baseUrl.js
   |     └── is-empty.js
   └── images for icons
```
This part is created with javascript for baseURl and empty.

## Screenshots :point_down: 

<div align="center">
       
For non-admin or ordinary users
       
<a href="pics/d0.jpeg"><img src="pics/d0.jpeg" width="250" height= "450"></a> <a href="pics/d1.jpeg"><img src="pics/d1.jpeg" width="250" height= "450"></a> <a href="pics/d2.jpeg"><img src="pics/d2.jpeg" width="250" height= "450"></a>
       
<a href="pics/d3.jpeg"><img src="pics/d3.jpeg" width="250" height= "450"></a> <a href="pics/d4.jpeg"><img src="pics/d4.jpeg" width="250" height= "450"></a> <a href="pics/d5.jpeg"><img src="pics/d5.jpeg" width="250" height= "450"></a>
       
<a href="pics/d6.jpeg"><img src="pics/d6.jpeg" width="250" height= "450"></a> <a href="pics/d7.jpeg"><img src="pics/d7.jpeg" width="250" height= "450"></a> <a href="pics/d8.jpeg"><img src="pics/d8.jpeg" width="250" height= "450"></a>
       
<a href="pics/d9.jpeg"><img src="pics/d9.jpeg" width="250" height= "450"></a> <a href="pics/d10.jpeg"><img src="pics/d10.jpeg" width="250" height= "450"></a> <a href="pics/d11.jpeg"><img src="pics/d11.jpeg" width="250" height= "450"></a>
       
For admin users this following part is additional       
       
<a href="pics/d12.jpeg"><img src="pics/d12.jpeg" width="250" height= "450"></a> <a href="pics/d13.jpeg"><img src="pics/d13.jpeg" width="250" height= "450"></a> <a href="pics/d14.jpeg"><img src="pics/d14.jpeg" width="250" height= "450"></a>
     
<a href="pics/d15.jpeg"><img src="pics/d15.jpeg" width="250" height= "450"></a> <a href="pics/d16.jpeg"><img src="pics/d16.jpeg" width="250" height= "450"></a> <a href="pics/d17.jpeg"><img src="pics/d17.jpeg" width="250" height= "450"></a>
       
<a href="pics/d18.jpeg"><img src="pics/d18.jpeg" width="250" height= "450"></a> <a href="pics/d19.jpeg"><img src="pics/d19.jpeg" width="250" height= "450"></a> <a href="pics/d20.jpeg"><img src="pics/d20.jpeg" width="250" height= "450"></a>
  
<a href="pics/d21.jpeg"><img src="pics/d21.jpeg" width="250" height= "450"></a> <a href="pics/d22.jpeg"><img src="pics/d22.jpeg" width="250" height= "450"></a> <a href="pics/d23.jpeg"><img src="pics/d23.jpeg" width="250" height= "450"></a>
</div>



