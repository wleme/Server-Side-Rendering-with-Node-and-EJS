#Angular Partials - Server Side Rendering with Node and EJS

You can use any Node template engine to render pages being requested by your angular app. One of the benefits of this approach is you can speed up your html development (if you use another template engine called Jade but here I'll use EJS) and your Angular app can also have some data ready when the page comes up, eliminating an API call. 

This app will have 2 routes

/server which will use EJS to template our Angular APP and also the server will send 2 values to the page: Title and a small list of books
/client which will be just html templating with some hardcoded values

[Original blog post]( http://williamleme.com/2016/01/angular-partials-server-side-rendering-with-node-and-ejs)