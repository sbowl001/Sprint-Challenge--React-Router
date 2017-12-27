1. What is the difference between _server side routing_ and _client side routing_?

server side routing - when clicking on a link, requests a new page from server. causes whole page to refresh 

client side routing - route handled by Javascript loaded on the page. when clicking on a link, request to server is prevented.  adjustment to url makes changed state of application. whole page wont refresh

1. Mention some advantages of using client side routing.

Advantages= because less data is processed, routing b/w views is faster

Smooth transitions and animations are easier to implement . 

1. Which component is used to define a route and what _props_ are commonly added to it?

Component used to define a route :  <Route>

Props commonly added are component, render, or children  ( which later = one of the render methods get passed 3 route groups: match, location, history)

1. How can I make sure that the component associated with the _"/"_ route is not displayed for every other route?

Write "exact" 