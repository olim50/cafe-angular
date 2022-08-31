## First step
1. Install development tools
2. Create Angular App
  a. Create project's folder
  b. Install @angular/cli
  c. Create App as frontend
3. Add Header (cd frontend/ng g c components/partials/header)
  a. Generate Component
  b. Add html
  c. Add css
4. List Foods
  a. Create Food model
  b. Create data.ts
    1. Add sample foods
  c. Add images to assets
  d. Create food service (ng g s services/food)
  e. Create Home component (ng g c components/pages/home)
    1. Add ts
    2. Add html   
      a. -> src\app\components\pages\home\home.component.html)
      b. (+ in src\app\app.component.html add <app-home>)
      c. add stars -> npm install ng-starrating --force
      d. in file src\app\app.module.ts in section imports:[] add RatingModule, class 'cook-time' and 'price'
    3. Add css in src\app\components\pages\home\home.component.css
5. Search
    1. Add method to Food service
    2. Add search route
    3. Show search result in Home component
    4. Generate search component (ng g c components/partials/search)
      1. Add to home component
      2. Add ts
      3. Add html
      4. Add css
6. Tags Bar
  1. Create Tag model
  2. Add sample tags to data.ts
  3. Food service
     1. Add get all tags method
     2. Add get all foods by tag method
  4. Add tags route
  5. Show tag result in Home component
  6. Generate Tags component
     1. Add to home component (ng g c components/partials/tags)
     2. Add ts
     3. Add html
     4. Add css
7. Food Page 
  1. Add method to food service
  2. Generate Food Page component (ng g c components/pages/food-page)
     1. Add Route
     2. Add ts
     3. Add html
     4. Add css
8. Cart Page
  1. Create CartItem Model
  2. Create Cart Model
  3. Generate Cart service (ng g s services/cart)
  4. Add to Cart Button in Food Page
  5. Generate Cart page component (ng g c components/pages/cart-page)
     1. Add Route
     2. Add ts
     3. Add html (ng g c components/partials/title)
     4. Add css
9. Not Found!

    Generate Component
    Add ts
    Add html
    Add css
    Add To Pages
    Home Page
    Food Page
    Cart Page
    Connect To Backend

    Create backend folder
    npm init
    npm install typescript
    Create tsconfig.json
    Create .gitignore
    Copy data.ts to backend/src
    npm install express cors
    Create server.ts
    install @types
    Add Apis
    npm install nodemon ts-node --save-dev
    Add urs.ts to frontend
    Add HttpClient module
    Update food service
    Login Page

    Generate Component

    Add to routes
    Add ts
    Add html
    Import Reactive Forms Module
    Add Css
    Add Login Api

    Use json
    Add jsonwebtoken
    Test Using Postman
    Generate User Service

    Generate User model
    Add User Subject
    Add Login Method
    Add User Urls
    Generate IUserLogin interface
    Add ngx-toastr
    Import Module
    Import BrowserAnimationsModule
    Add styles in angular.json
    Add to Header
    Add Local Storage methods
    Add Logout Method
    Add to Header
    Make Components For Login Page

    Input Container
    Input Validation
    Text Input
    Default Button
    Connect Login API To MongoDB Atlas

    Moving Apis into routers
    Create MongoDB Atlas
    Create .env file
    Install
    mongoose
    dotenv
    bcryptjs
    express-async-handler
    Connect to MongoDB Atlas
    Use MongoDB instead of data.ts in apis
    Register User

    Add Register api
    Add Register service method
    Add Register link
    Add Register Component
    Loading!

    Add Image
    Add Component
    Add Service
    Add Interceptor
    Checkout Page

    Create Order Model
    Create Checkout Page Component
    Add To Router
    Add User to User Service
    Add Cart to Cart Service
    Create Order Items List Component
    Adding Map To The Checkout Page
    Add Leaflet npm package
    Add @types/leaflet
    Add Css to angular.json
    Add AddressLatLng to Order Model
    Create Map component
    Add to checkout page
    Add TS
    Change app-map selector to map
    Add Html
    Add CSS
    Add Auth Guard
    Save Order
    Add Order Model
    Add Order Status Enum
    Add Auth Middleware
    Add Order Router
    Add create API
    Add Order Urls to urls.ts
    Add Order Service
    Add create Method
    Add Auth Interceptor
    Payment Page

    Generate Component
    Add 'getOrderForCurrentUser' api
    Add Order Service method
    Connect Component to Service
    Make the map component readonly
    Adding Paypal

    Generate Component
    Add to payment page
    Get Paypal client Id
    Add Paypal JS to index.html
    Set up Paypal button
    Add Pay api to order router
    Get Paypal sandbox account
    Order Track Page

    Generate Component
    Add to routes
    Add API
    Add to urls.ts
    Add method to order.service
    Add HTML
    Add CSS
    Deploy On Heroku

    OutputPath in angular.json
    package.json
    frontend
    backend
    root
    BASE_URL in urls.ts
    Public folder config in server.ts
    Run commands
    Add built folder to .gitignore
    Commit and Push
