CRUD through HTTP is a good step forward to using resources and becoming RESTful, another step further into it is to make use of hypermedia based services and this gem allows you to do it really fast.

You can read the article on [using the web for real](http://guilhermesilveira.wordpress.com/2009/11/03/quit-pretending-use-the-web-for-real-restfulie/), which gives an introduction to hypermedia/resources/services.

Why would I use restfulie?

1. Easy --> writing hypermedia aware resource based clients

2. Easy --> hypermedia aware resource based services

3. Small -> it's not a bloated solution with a huge list of APIs

4. HATEOAS --> clients you are unaware of will not bother if you change your URIs

5. HATEOAS --> services that you consume will not affect your software whenever they change part of their flow or URIs

[You can read all documentation here](http://github.com/caelum/restfulie-java)