# PostPostman

Pospostman is an application of applicative monitoring (fully http monitoring) by using Postman collections.
For installing server side on containers please see the instructions wiki page:
`https://github.com/EASS-HIT-2022/PostPostman/wiki/SERVER-SETUP`
> In order to use the application (till client side will be developed) you should:
> 1. create collection at Postman. Example `https://learning.postman.com/docs/getting-started/creating-the-first-collection/`
> 2. click settings -> share -> via JSON link and save the link.
> 3. use API /monitor/ put request to create monitor with the saved link. 
> 4. run it whenever you want to by /executor/execute. It will also be runned once an hour.
