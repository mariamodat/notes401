# Do a Simple HTTP Request in Java
## how HTTP request is done ?
it's a way of performing HTTP requests in Java by using the built in Java class HttpUrlConnection. 

**what is HttpURLConnection** ? 
HttpURLConnection class is an abstract class directly extending from URLConnection class.
## uses of HttpURLConnection :
![imh](https://cdn.journaldev.com/wp-content/uploads/2015/03/java-HttpURLConnection.png)

 **how we can Create a Request?**
 * Create URL object from the GET/POST URL String.
 * Call openConnection() method on URL object that returns instance of HttpURLConnection.
 * Set the request method in HttpURLConnection instance, default value is GET.
 
 EX: 

URL url = new URL("http://example.com");

HttpURLConnection con = (HttpURLConnection) url.openConnection();

con.setRequestMethod("GET");
