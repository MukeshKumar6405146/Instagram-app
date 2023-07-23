# Instagram-app
Making Instagram Backend using  java-Spring-Boot framework

Creating Backend functionality of Instagram  with java-Spring-Boot
Where User can register him/her.We are using JWT tokens for authentication
User can post, can like and comment on a post.
User can follow another user

App Has following properties as Entities
* User
* Post
* Like
* Comment
* Follow
* Admin
* Authentication

  #### our project is having following endpoints
   * addAllUser 
   * getAllLikes
   * getAllComments
   * getAllFollowers
   * posts
   * posts/like
   * posts/comment

## Frameworks and languages used
* Spring
* java
* maven
* Hibernate-validation
* Regex for validating patterns
* H2 Database
* JWT tokens

## Data Flow
 * Controller<br>
         <p>- It is just containg Api endPoint and logic for<br> 
           what should this api do.</p>
* Services<br>
        <p>- It has actual logic(business logic) for method.<br> 
          It is also called Model.</p>
       
 * Repository<br>
           - It is having data source
 * Model
      ```
       <P> It has the actual model of<br>
                 - User<br>
                 - Admin<br>
                 - Post<br>
                 - Follow<br>
                 - Like<br>
                 - Comment<br>
                 - Authentication<br>
   what properties they have as Entity.</P>
    ```
                 

 ## Data Structure
   * Here we are using List(ArrayList) datastructure to store and manipulate data.
