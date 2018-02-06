Altran Api Rest Full Consumer

Web application to consume Node api REST full "altran-api-rest-full-node-express".
Previous configurations:

- In order to correctly execute the link between this application and the API, it must be hosted on a server (LAMPP or XAMPP, for example).
- Run api node (a script is programmed for the effect: npm start). It uses port 3000.
- Access the application through the browser's address bar (by default: http://127.0.0.1/altran-api-rest-full-consumer)


Mode of use:

The website is designed to allow access to user or policy information, with the following considerations:

- Before being able to make any query, you must login. The login validates if an authentication token exists, and if not, it creates it (obviously, if the user is valid)
- Once logged in, you will have access to user queries (through your id or name) or to the policies (through the user name or policy number).
- The access to the information is restricted to the role of the logged in user, therefore, before carrying out the different consultations, it validates against the roles of users with allowed access. 
