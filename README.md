[![Build Status](https://travis-ci.org/markwei92/ecommerce-assignment.svg?branch=master)](https://travis-ci.org/markwei92/ecommerce-assignment)
#Fashion Apparel Ecommerce Project

This project is an ecommerce clothing s"tore whereby users can browse the store and make online purchases on their desired products.


#UX

As a user, they can browse the store and when they are ready to make a purchase, they will have to sign up for an account on my website in order to be able to add the goods to cart and checkout.
The design is relatively simple, with a display that shows all the products on a single page as it is a small niche business, pictures and other media contents are stored on AWS server and the website is hosted on heroku via postsgresl.

#Features

Users scroll through the catalogue of products or use the search function. There are pictures, descriptions, sizing and pricing of the product. Users can also select their products by adding to cart using the up and down button or just keying it in manually.
When they are ready to buy they can register an account by clicking on the register tab on the navbar and fill out all the necessary details and click the create account. 
Users are required to sign up for an account at the register tab before they can proceed to checkout and make payment.
Users will then fill in all the necessary card payment details and address details to process payment, if the credit card is not a valid one there will be a message that states that the card cannot be processed and that the payment is unsuccessful.


#Frameworks Used

This project is a full stack project consisting of html, css, bootstrap, javascript, python and django framework with postgresl.
Much of the website layout and structure is based off the tutorial provided by Code Institute such as the libraries and Django framework.


#Testing

For testing, I did manual testing, testing the registration by signing up for an account and checking the admin to see if the account exists, thereafter trying the login and logout functions. I also tested to ensure user account created do not have
administrative rights to the site. Next I tested the search box function by typing in various search terms, and the search returned back accurately the results based on the keyword I typed in. Thereafter I clicked on the Brand name at the top left of the site to test whether it will return back to the home page and it worked as expected. 
Next I tested the add to cart functions in the homepage as well as the add to cart page to ensure that the cart can be updated accordingly. Lastly I tested the checkout function and keyed in the fictious details, I expected
payment to be unsuccessful as the card details are not valid and displays the error message as expected.

#Deployment

Deployed to Github, AWS and Heroku. Github was straightforward, however AWS and heroku were more steps intensive and required a couple of tries to get the website to work seamlessly.


#Credits

Credits to Code Institute for web layout and design.

#Media & Content
The photos used in this site were obtained from:
1) https://www.686.com/products/686-mens-glcr-everywhere-multi-shell-pant
2) https://www.adidas.com.sg/crew-socks-3-pairs/S21490.html
3) https://www.amazon.in/MarkQues-Executive-Genuine-Leather-EXE-1101/dp/B073B8RVFG
4) https://www.jackjones.com/ie/en/jj/clothing/t-shirts/polo-shirts/slim-fit-polo-shirt-12151449.html?cgid=jj-tshirts-polo
5) https://www.target.com/p/men-s-standard-fit-button-down-dress-shirt-goodfellow-co-153/-/A-52491986
6) https://www.express.com/clothing/men/extra-slim-paisley-stretch-cotton-dress-shirt/pro/06034393/cat1840002 or 
https://www.google.com/search?rlz=1C1CHBF_enSG845SG846&biw=1536&bih=674&tbm=isch&sa=1&ei=bFzvXO2zILjDz7sP4LSusA0&q=shorts&oq=shorts&gs_l=img.3..0l10.94450.95378..101355...0.0..0.373.893.4j0j1j1......0....1..gws-wiz-img.......35i39j0i67.Yt-CmoJMl1o#imgrc=LLrXIXspLNGtYM: