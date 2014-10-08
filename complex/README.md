You can put your REST files in the same directory, and then point to the directory to generate all methods in one controller.
For instance, try:

```
r2m gen -e user-manager
```
Under the mobile directory, this will create a RestController class for iOS, Javascript and Android containing the createUser, deleteUser, updateUser, and listUsers methods.
