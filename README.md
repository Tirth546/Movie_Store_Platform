# MovieStoreMvc

Purpose of the Project:-

The Movie Store Admin Panel is a web-based application designed to allow administrators to manage the movie database efficiently. This project provides essential functionalities for adding, editing, and deleting both movies and genres. The goal is to create a streamlined and user-friendly interface that enables admins to maintain the movie catalog, ensuring the platform's content remains current and organized.

Now upgraded to .net 8.0

# How to run it

1. clone the project
2. open `appsettings.json` file and update connection string's `data source=your server name`

   ```
    "ConnectionStrings": {
          "conn": "data source=your_server_name;initial catalog=MovieStoreMvc; integrated security=true;encrypt=false"
     }
   ```

3. Delete `Migrations` folder
4. Open Tools > Package Manager > Package manager console
5. Run these 2 commands
   ```
    (i) add-migration init
    (ii) update-database
   ```
6. Now you can run this project
