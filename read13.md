# Working with Relationships in Spring Data REST
# One-to-One Relationship
@OneToOne relationship is to use @MapsId. This way, you don’t even need a bidirectional association since we can always fetch the PostDetails entity by using the Post entity identifier.
* we should have different names for each association resource , this leads to an exception called : “Detected multiple association links with same relation type! Disambiguate association”.

## Repository 
we have to create two interfaces repository both extend **CrudRepository interface**.
## Creating the Resources
the resources are the data ,and because URL is not adequate for handling all kinds of low level resources, Spring introduced org.

we must return an epmty object at first.
ex: ![img](https://www.programmersought.com/images/444/44519393fa474d3ea801317cbad8eddc.png)


#  One-to-Many Relationship
**@OneToMany**
we can use @RestResource to use a custom association resource.
** we have to create a Repository.

# Many-to-Many Relationship
create two repository interfaces for each of them, by extending the CrudRepository interface.
# Mocking Web Context Beans
MockMvc provides support for Spring MVC testing. It encapsulates all web application beans and makes them available for testing.