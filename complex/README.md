You can put your REST files in the same directory, and then point to the directory to generate all methods in one controller.

Copy locally the user-manager directory. For instance with:
```
svn export https://github.com/magnetsystems/r2m-examples/trunk/complex/user-manager
```
Then run:

```
r2m gen -e user-manager
```
Under the mobile directory, this will create a RestController class for iOS, Javascript and Android containing the createUser, deleteUser, updateUser, listUsers, and login methods.
