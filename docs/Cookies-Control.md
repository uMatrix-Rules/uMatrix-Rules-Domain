As how it says in [uMatrix wiki](https://github.com/gorhill/uMatrix/wiki/Cookies), uMatrix will prevent cookies `from leaving your browser`.  
By following rule sets bellow you do do further:

Add rule `* * cookie block`, which means to block cookies globally by default. You can then allow them in any specific scope where you are to login. Here is an example:

    * * cookie block
    google.com accounts.google.com cookie allow
    google.com google.com cookie block

In this case, `google.com google.com cookie block` prevent cookie-based tracking from Google search but, meanwhile, `google.com accounts.google.com cookie allow` can allow you to login to some Google service.