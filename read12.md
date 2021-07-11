# Spring RequestMapping
this request hadles(Maps) the http method (request)
we must notice that the RequestMapping has no default , so it may map to any http request.
## Using @RequestMapping With Producible and Consumable
* to use produce :  we use @RequestMapping in combination with the @ResponseBody annotation.(Response)
* to use consume : we use to consume @RequestMapping in combination with the @RequestBody annotation.(Request)

this may explain :
![img](https://slidetodoc.com/presentation_image_h/81c48a973442c36586cca904dce4166c/image-52.jpg)

## RequestMapping With Path Variables
*  Single @PathVariable ----> ex :
 @RequestMapping(value = "/ex/foos/{id}", method = GET)

@ResponseBody

public String getFoosBySimplePathWithPathVariable(
  @PathVariable String id) {

    return "Get a specific Foo with id=" + id;
}
**Here you can notice that we passed one variable in the path {id}**

* Multiple @PathVariable ------> ex: 
@RequestMapping(value = "/ex/foos/{fooid}/bar/{barid}", method = GET)

@ResponseBody

public String getFoosBySimplePathWithPathVariables
  (@PathVariable long fooid, @PathVariable long barid) {

    return "Get a specific Bar with id=" + barid + 
      " from a Foo with id=" + fooid;
}

**Here you can notice that we passed two variables in the path {fooid} &{barid}**

## RequestMapping With Request Parameters
it's used to bind a web request parameter to the parameter of the handler method

this could explain :
![img](https://candidjava.s3.amazonaws.com/post/springmvc/URLParameter-requestparam/requestMapping-URLParameters2a.png)

## @RequestMapping — a Fallback for All Requests
this is used to implement a fallback for all requests using  http methods.
we use the (*) to annotate for all requests , ex : 

@RequestMapping(value = "*", method = RequestMethod.GET)

@ResponseBody

public String getFallback() {

    return "Fallback for GET Requests";
}