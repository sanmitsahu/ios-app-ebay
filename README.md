# ios-app-ebay

Video Link - https://youtu.be/7UDws7lmIe8?si=tDh8dhIzwyclEiwx

The project is a mobile application developed for the iOS platform, specifically designed for iPhones and iPads. The primary goal of the application is to enable users to search for products using eBay APIs, retrieve detailed information about the products, add them to a wishlist, and share product details on Facebook. The application is built using the Swift programming language and leverages the Xcode IDE for iOS app development.

**Swift Language and Xcode**: The project utilizes Swift, a general-purpose programming language developed by Apple, for iOS, macOS, watchOS, and tvOS development.
Xcode, Apple's integrated development environment (IDE), is employed for software development, providing features such as Swift 5 support, Playgrounds, Interface Builder, device simulation, user interface testing, and code coverage.

**iOS:** The application is designed to run on Apple's iOS, the mobile operating system powering devices like iPhone, iPad, and iPod touch.

**SwiftUI:** SwiftUI, an innovative and declarative way to build user interfaces across Apple platforms, is used for creating the app's UI. It allows developers to use a single set of tools and APIs for building interfaces on various Apple devices.

**SF Symbols:** SF Symbols, a library of iconography designed to integrate seamlessly with the San Francisco system font, is employed. It includes over 3,300 symbols with various weights and scales, enhancing the app's visual elements.

**Xcode Design Tools:** The project makes use of Xcode's design tools to keep code and design in sync. It leverages features like dynamic type support, Dark Mode, localization, and accessibility.

Ba**ckend Development (Node.js):** The app interacts with a backend developed in Node.js, running on GCP. It includes APIs for tasks like searching for products, getting details, adding to wishlist, and posting on Facebook.

**Asynchronous Networking:** Asynchronous HTTP requests are made to the backend using libraries such as Alamofire for making HTTP requests, Kingfisher for rendering images, PromiseKit for handling asynchronous requests, and SwiftyJSON for parsing and handling JSON data.

**Location Services:** The app utilizes location services to determine the user's current location when custom location is turned off. 

**Database (MongoDB):** MongoDB is used to store wishlist data. The app interacts with MongoDB to add, remove, and display wishlist items.

**Validation and Error Handling:** The project implements validation for user input, ensuring that appropriate messages are displayed for validation errors. Error handling is implemented throughout the app to provide a smooth user experience.

**TabView and Navigation:** TabView is employed for navigation within the app, allowing users to switch between different sections. Navigation bars and elements like back buttons are used for seamless user navigation.

**API Integration (eBay and Google Customized Search):** The app integrates with eBay API for product information and Google Customized Search API for fetching images based on product titles.

**User Interface Design:** The app follows a clean and visually appealing design using SwiftUI, incorporating features like carousels, pickers, checkboxes, and buttons for an interactive user experience. Navigation within the app is facilitated by elements like TabView, NavigationView, and Navigation Bar.

**Product Search and Wishlist:** Users can enter search queries, select categories, specify conditions, and set other filters for product search. Wishlist functionality allows users to add or remove products, with wishlist data stored in MongoDB.

**Product Details and Sharing:** Detailed product information is displayed, including images, title, price, shipping details, and condition. Users can share product details on Facebook, opening a web page for sharing.

**Additional Features:** Implements a wishlist screen with the ability to switch between search and wishlist views. Supports deletion of wishlist items through swipe gestures.

_In accordance with class policy, code shared only on demand from prospective employers._
