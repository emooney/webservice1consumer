# webservice1consumer

modeled from:
https://spring.io/guides/gs/consuming-rest/

This Webservice Consumer Spring app goes out to a service that returns random quotes. The endpoint is http://gturnquist-quoters.cfapps.io/api/random.
A 'Quote' object is passed along with the endpoint to Spring's RestTemplate class and a populated Quote object is returned.
This happens in a CommandLineRunner instance that is called from the Application's main().
