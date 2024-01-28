# Blogpost-app-microservice-architecture
 
<p align="center">Blogpost app with a microservice architecture made with node.js and react with features like creating posts and comments along with automatic moderation built in.</p> 
<p align="center">After running the project and after posting some posts and comments try closing one of the services the projects and not still open services will still be running. And the moderated word is 'orange' , try commenting orange🍊🍊🍊 under the posts. It should be moderated . Why the 🍊 because I love it. </p>
<img src= "https://github.com/bijin-s/blogpost-app-microservice-architecture/blob/main/assests/app%20homepage.png">
<h2>Architecture</h2>
<p>It consist of 6 different services run parallely and talking with each other 
<ul> 
<li>client</li>
<li>posts</li>
<li>comments</li>
<li>moderation</li>
<li>query</li>
<li>event-bus</li>
</ul>

</p>

**Prerequisites:**
Ensure you have Node.js and npm installed on your machine. You can download it from [Node.js official website](https://nodejs.org/).


**Installation Steps:**

1. **Clone the Git Repository:**
    ```bash
    git clone https://github.com/bijin-s/blogpost-app-microservice-architecture.git
    ```
    Clone the repository containing the finance tracker project.

2. **Navigate to the Project Directory:**
    ```bash
    cd blogpost-app-microservice-architecture
    ```

3. **Install Dependencies:**
    ```bash
    npm install
    ```
    This command installs all the necessary dependencies required  project.<br/>

    
**Running the Project:**

1. **Run all the 6 services by going to each directory :**
    ```bash
        npm start
        ```
All the services must be working intially for the project to work


<img src= "https://github.com/bijin-s/blogpost-app-microservice-architecture/blob/main/assests/cmd%20services%20photo.png">


## License
This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
