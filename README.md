# Best practice when you write an API

## Some of the points to consider while writing an API:

  - Write for human.
  > Example: ```/users/{id}/card-number``` instead of ```/users/{id}/pin```.

  - Should use lower case letters.
  > Example: ```/users/{id}/pending-orders``` instead of ```/users/{id}/Pending_Orders```.

  - Separate words with dashes.
  > Example: ```/users/{id}/pending-orders``` instead of ```/users/{id}/pending_orders```.

  - Follow the naming pattern similar to the folder structure.

  - Use Hierarchy.

  - Keep in mind while designing an API is maintaining the version number in the API.
  
  - No trailing forward slash.
  > Example: ```/users/{id}/pending-orders``` instead of ```/users/{id}/pending-orders/``` and both should give the same output.
