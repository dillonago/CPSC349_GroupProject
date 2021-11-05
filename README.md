# CPSC 349-02 Group Project 1, Team 2DE
> Dillon Go (Team lead)
>
> Evan Le
>
> Dylan Ngo
>
> Elnathan Yoon

# INSTRUCTIONS ON HOW TO INSTALL, CONFIGURE, AND RUN THE APPLICATION ON YOUR COMPUTER
1. Clone this repository. (Hit "Code" green button, copy the link. In terminal, find where you want to clone it too, and run 'git clone <link>')

2. Download all the libraries and packages by running 'npm install'
a. (If on VSCode, you can open the file and use the terminal on there to do so but if not, you must run 'cd CPSC349_GroupProject' before you do so)

3. If there is no .env file when you clone the repository, you will have to make on yourself. It will be 2 lines with the variables:
   DB_CONNECT = <link to your MongoDB database>
   TOKEN_SECRET = <Random characters for the encryption>
  
4. Run the Application using either of these commands:
  'npm start' or 'node server.js'
  
5. If you are missing any packages, you can install them by running 'npm install <package name>'.
