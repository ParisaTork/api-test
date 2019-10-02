# api-test (Java)

## API Basics

**What is an API?**

- [What is an API?](https://www.youtube.com/watch?v=s7wmiS2mSXY)

**HTTP Methods**

- _**GET**_: **Retrieve data from a specified resource** e.g. browser client makes GET requests every day by going to a specific server URI a.k.a. a website
- _**POST**_: **Submit data to be processed to a specified resource** e.g. filling out webforms, form tags in HTML can take an action (page you're submitting to) and a method attribute (GET/POST etc.)
- _**PUT**_: **Update a specified resource** - e.g. updating a blog post - N.B. you would need to send requests to an endpoint/URI with an ID for that specific resource, for forms you'd need to send an AJAX request
- _**DELETE**_: **Delete a specified resource** - N.B. you would need to send requests to an endpoint/URI with an ID for that specific resource
- _**HEAD**_: **Same as GET, but does not return a body, only HEAD info**
- _**OPTIONS**_: **Returns the supported HTTP methods of a server**
- _**PATCH**_: **Update partial resources**

**API Authentication**

- ```curl -H "Authorization: token OAUTH-TOKEN" https://api.github.com```

Uses a token for authentication - N.B. replace OAUTH-TOKEN in real life

- ```curl https://api.github.com/?access_token=OAUTH-TOKEN```

Also uses a token for authentication - N.B. replace OAUTH-TOKEN in real life

- ```curl 'https:api.github.com/users/whatever?client_id=xxxx&client_secret=yyyy'```

Uses a client ID and a client secret for authentication -  N.B. replace client_id + client_secret in real life

- ```curl 'https:api.github.com/users/whatever?client_id=xxxx&client_key=yyyy'```

Uses a client ID and a client key for authentication -  N.B. replace client_id + client_key in real life

**Terminology**

- **Endpoints** - The URI/URL where an API/service can be accessed by a client application e.g. ```https://mysite.com/api/users```
- _**curl**_ - cURL/curl is a command-line tool for getting or sending files using URL syntax.

## Using IntelliJ IDE

<strong>Sending HTTP Requests</strong>
- [Using java.net.HttpURLConnection - source code](https://github.com/ParisaTork/api-test/blob/HTTPURLCONNECTION/src/com/company/Main.java)
- [Using java.net.http.HttpClient - source code](https://github.com/ParisaTork/api-test/blob/HTTPCLIENT/src/main/java/com/company/Main.java)

<strong>Parsing JSON Data</strong> 

**N.B. Add [JSON in Java](https://mvnrepository.com/artifact/org.json/json/20190722) to your POM file**
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

![Imgur](https://i.imgur.com/28RjR3Bl.png)

Source: https://idratherbewriting.com/learnapidoc/docapis_understand_curl.html


## Postman (a collaboration platform/GUI for API development)

Source: https://www.taniarascia.com/making-api-requests-postman-curl/

## Nutritional information APIs

- Edamam
- FoodData Central (US Gov.)
- MyFitnessPal
- Nutritionix
