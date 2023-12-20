## Task 1

- Log into AWS as root user, create a user (test-user-1). Accept defaults and do not allocate any policies
- Check if test user can log in with default (generated) password and user is forced to change the password
- Try S3 and see if user can see list of buckets or attempt to create bucket

## Result

- Since use do not have any policies yet, user will see permission errors

## Task 2

- Create a user group
- Assign user to user group
- Assign S3 full access policy to group
- Test user
