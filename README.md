# api-test (Java)

## What is an API?

- [What is an API?](https://www.youtube.com/watch?v=s7wmiS2mSXY)

## HTTP Methods

- GET: **Retrieve data from a specified resource** e.g. browser client makes GET requests every day by going to a specific server URI a.k.a. a website
- POST: **Submit data to be processed to a specified resource** e.g. filling out webforms, form tags in HTML can take an action (page you're submitting to) and a method attribute (GET/POST etc.)
- PUT: **Update a specified resource** - e.g. updating a blog post - N.B. you would need to send requests to an endpoint/URI with an ID for that specific resource, for forms you'd need to send an AJAX request
- DELETE: Delete a specified resource - N.B. you would need to send requests to an endpoint/URI with an ID for that specific resource
- HEAD: Same as GET, but does not return a body, only HEAD info
- OPTIONS: Returns the supported HTTP methods of a server
- PATCH: Update partial resources

## Using IntelliJ IDE

<strong>Sending HTTP Requests</strong>
- [Using java.net.HttpURLConnection - source code](https://github.com/ParisaTork/api-test/blob/HTTPURLCONNECTION/src/com/company/Main.java)
- [Using java.net.http.HttpClient - source code](https://github.com/ParisaTork/api-test/blob/HTTPCLIENT/src/main/java/com/company/Main.java)

<strong>Parsing JSON Data</strong>
- [Parsing JSON Data, using java.net.HttpURLConnection - source code](https://github.com/ParisaTork/api-test/blob/PARSEHTTPURLCONNECTION/src/main/java/com/company/Main.java)
- [Parsing JSON Data, using java.net.http.HttpClient - source code](https://github.com/ParisaTork/api-test/blob/PARSEHTTPCLIENT/src/main/java/com/company/Main.java)

<strong>Documentation (for the above)</strong>
- [Oracle HttpURLConnection docs](https://docs.oracle.com/en/java/javase/12/docs/api/java.base/java/net/HttpURLConnection.html)
- [Oracle HTTPClient docs](https://docs.oracle.com/en/java/javase/12/docs/api/java.net.http/java/net/http/package-summary.html)

<strong>Demo (for the above)</strong>
- [How to Send HTTP Requests and Parse JSON Data Using Java](https://www.youtube.com/watch?v=qzRKa8I36Ww)

<strong>Resources</strong>
- [JSON Placeholder](https://jsonplaceholder.typicode.com/) (Fake Online REST API for Testing and Prototyping)

## Terminal

- [Test a REST API with curl](https://www.baeldung.com/curl-rest)

## Postman (a collaboration platform for API development)

## Nutritional information APIs

- Edamam
- FoodData Central (US Gov.)
- MyFitnessPal
- Nutritionix
