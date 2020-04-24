# Covid-info
Covid-info/help is a website that serves two main purposes. Firstly it's an information site on Covid-19. It displays real time statistics of world(country-wise) and India(state-wise and district-wise) regarding Covid-19 condition. Users can also get information about Covid-19 testing centers, helpline-nos, NGO's, Hospitals, etc. available in various cities of India. The website also has a unique news feature that renders 10 latest news related to Covid-19 of the place entered by the user. 
Secondly, through Covid-help website small business shops can take their stores online. ShopOwners will be able to accept online orders, easily maintain record of orders and generate computerised bill. Maps feature is also added for easy navigation to shops.



# Motivation
 The very world we know and love is changing by the second due to the spread of COVID-19. People are stuck in their houses and are badly impacted by this crisis. People are very curious about questions like -
 * How many cases has my City registered
 * What is the totals number of active cases in India or Worldwide
 * What are the latest news regarding Covid-19 of my city
 * Are there any Covid testing labs, hospitals, free food shelters, NGOs, etc. nearby me
 * Which phone number to dial in case of emergency?
 All these questions were the basis of our Covid-info project and we tried to create a one-stop solution for all questions.
 
Another problem faced by people now is crowding of people in front of grocery stores while collecting orders. This leads to total disruption of the concept of social distancing. So our team thought of designing a website where these small grocery stores can take their stores online. People can place online orders from home and come to the shop to directly collect their order. Thereby reducing the need to wait in long queues and also enforce social distancing. Therefore we have launched Covid-help website. 


# Code style
If you're using any code style like xo, standard etc. That will help others while contributing to your project. Ex. -



# Screenshots



# Tech/framework used
The following tools were used in building this site
* Front-end development
  * HTML
  * CSS
  * BootStrap 
  * Semantic UI
  
* Back-end development
  * Javascript
  * Node.js
  * Express.js
  * jQuery
  
* Database used
  * mongodb
  
* Authorisation/Authentication
  * passport.js
  
* Web- Scrapping
  * puppeteer.js

* Graphical tools
  * d3.js
  * Scalable Vector Graphics (SVG)
  
* Maps
   * mapmyindia API



# Features
* Covid-info
  * Recent statistics of Covid-19 confirmed, active, recovered, deaths cases of world(country-wise) and India(state-wise and district-wise) rendered in tabular format.
  * Graphical Representation of data for better understanding.
  * Choropleth map of world and India for better data visualisation.
  * Accurate and Effective news scrapper that renders 10 latest news of a place.
  * Additional important information like - Covid-19 testing centers, Hospitals, Govt. Helpline nos., Free food services, Shelter homes and much more.
  * User interactive website. Responsive for desktop and mobile use.
  * Additional risk checker of Covid-19 for users.
 
 
* Covid-help
  * Small shops and businesses can currently take their business online by signing up on our website.
  * Maps feature added for easy location and indentification of shops by users.
  * Extremely simple to place orders.
  * Easy maintainance of order data as 'New Orders', 'Payment Pending Orders', 'Completed Orders' category.
  * Search orders by buyer name, phone no., order date.
  * Each order has a unique id to prevent order mismatch. Also date and time of order is also recorded.
  * Easy bill generation and downloadable in PDF format.
 

* Authentication
  * Secure Authentication features implemented with passport.js
  * No two usernames can be same.
  * No two shops can have same ids
  * User cannot use the features of our site without being logged in.
 
* Additional feat ures
  * Well sanitized code base and easy to maintain
  * All RESTful routes followed and proper routes maintained.
 
 





# Code Example
Show what the library does as concisely as possible, developers should be able to figure out how your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.



# Installation
It is very easy to use our project if anyone wants. Just follow the steps :

1. Firstly if you are working locally then you need to install the following :
    * Node.js
    * MongoDB
    * VS Code ( recommended , Any other suitable code editor will work )
  
2. Next you need to our project's GitHub repository to your desktop 

3. Open command line navigate to the project folder. Then type the following commands to install required dependencies :
    * npm install async, body-parser, connect-flash, ejs, express, express-session, locus, method-override, mongoose, passport, passport-     local, passport-local-mongoose, puppeteer, request --save
  
4. After successful installation run the command *node app.js* to start the project. If you see *Server Has Started!!* then you have        successfully setup everything and good to go with our application.







# API Reference
The following API's were used used to fetch Covid-19 data for our website that renders data in JSON format
  * [https://corona.lmao.ninja/v2/countries](https://corona.lmao.ninja/v2/countries)
  * [https://api.covid19india.org/state_district_wise.json](https://api.covid19india.org/state_district_wise.json)
  * [https://api.covid19india.org/data.json](https://api.covid19india.org/data.json)
  * [https://api.covid19india.org/resources/resources.json](https://api.covid19india.org/resources/resources.json)
  
The project also uses Maps api of mapmyindia.org to render maps
 * [https://www.mapmyindia.com/api/advanced-maps/doc/interactive-map-api](https://www.mapmyindia.com/api/advanced-maps/doc/interactive-map-api)

---

#Tests
####Describe and show how to run the tests with code examples.



---

#How to use?
####If people like your project they’ll want to learn how they can use it. To do so include step by step guide to use your project.


---

#Contribute
####Let people know how they can contribute into your project. A contributing guideline will be a big plus.



---

#Credits
####Give proper credits. This could be a link to any repo which inspired you to build this project, any blogposts or links to people who contrbuted in this project.



---

#License
####A short snippet describing the license (MIT, Apache etc)

