
# Peddy

### Peddy is a dynamic web application that displays a collection of pets available for adoption or sale. The project fetches real-time data from an API, sorts the pets by price, and presents them in a responsive grid layout with images. Users can browse and view pet details, ensuring a seamless and engaging experience across all devices.

## 5 key features of the project:

1. Add dynamic categories through API: Fetch and display different pet categories dynamically from an external API.
2. Perform sorting: Sort the list of pets based on criteria such as price, making it easier for users to find what they’re looking for.
3. Add all posts dynamically via API: Fetch and dynamically display posts (pets) using data from an API.
4. Display post details: Show detailed information for each pet, including image, price, and description.
5. Include an adopt button: Provide users with an "Adopt" button for each post, making it easy to take action directly from the listing.

## used ES6 features:

In the provided JavaScript code, several ES6 features are utilized:

1. Arrow Functions:

Functions like categoryFun, displayCategory, sort, and others are defined using the arrow function syntax (=>), which is more concise compared to traditional function expressions.

2. Template Literals:

Template literals are used extensively for creating HTML strings within div.innerHTML. This allows for embedded expressions using ${} and multiline strings without concatenation.

3. Optional Chaining:

The code uses optional chaining (?.) to safely access deeply nested properties like item?.category_icon, item?.pet_name, and data?.pets. If the property is null or undefined, it returns undefined instead of throwing an error.

4. Async/Await:

Asynchronous code is handled using async and await for better readability and handling of promises. Functions like categoryFun, sort, allPosts, searchCategoryFun, and detailsFun fetch data asynchronously using await.

5. let and const:

Block-scoped variable declarations with const and let are used throughout, which helps prevent variable hoisting issues. For example, const posts = document.getElementById("posts");.

