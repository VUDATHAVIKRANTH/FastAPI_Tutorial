Basic Operations performed used APIS are CRUD


# GET Method
 when we want to get any information from the server we use get method.
 the response we receive from the server will be in JSON Format

 eg:
 @app.get("/")
 def root():
   return {"message":"you are in the root directory")

 ## Path Parameters
 while performing retrivel operation if we have dynamic endpoint then we use path parameter
 eg: 
 @app.get("/fetch_posts/{id}")
 def fecthing(id):
  fetch operation

## Query Parameters
 while we want to filter the parmaters then we use Query Parameters

# POST Method

when we want to send data to server to store in it we use post method. the post request should have request body and should be in JSON format.

data that is being send should be validated.

<img width="526" height="320" alt="image" src="https://github.com/user-attachments/assets/d05d4b83-9768-4398-9fc3-770861d2a965" />

<img width="303" height="107" alt="image" src="https://github.com/user-attachments/assets/e4bd8c5a-4a53-4214-b8a2-5fd1dbc0d6f2" />

# PUT Method

