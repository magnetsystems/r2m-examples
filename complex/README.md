# More complex examples

## Generating all methods in one class

You can put your REST files in the same directory, and then point to the directory to generate all methods in one controller.
For instance, try:

```
r2m gen -e user-manager 
```

This generates mobile controllers for Android, Javascript and iOS under the mobile directory. Each controller contains a createUser, deleteUser, updateUser, and listUser method. 
