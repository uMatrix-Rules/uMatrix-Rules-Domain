## [Vrooboo! Wabbo!!](https://rictusempra.github.io/uMatrix-Rules/#Ovagarava)

As how it says in [uMatrix wiki](https://github.com/gorhill/uMatrix/wiki/Cookies), uMatrix will prevent cookies `from leaving your browser`.
By following rule sets bellow you do do further:

Add rule `* * cookie block`, which means to block cookies globally by default. You can then allow them in any specific scope where you are to login. Here is an example:

    * * cookie block
    google.com accounts.google.com cookie allow
    google.com google.com cookie block

In this case, `google.com google.com cookie block` prevent cookie-based tracking from Google search but, meanwhile, `google.com accounts.google.com cookie allow` can allow you to login to some Google service.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>
Except where otherwise noted, all content in this repository is licensed under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0 International License</a>
