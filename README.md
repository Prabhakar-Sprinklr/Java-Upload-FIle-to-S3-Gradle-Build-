# Java-Upload-FIle-to-S3-Gradle-Build-

This program is a client to upload a file to an AWS S3 Bucket.

In the Project Directory, there is a application.yml file under resources,
provide the access key and secret key as generated over your AWS account,
then fill the name of the bucket along with the region where the bucket
is created in.

Then to build and run over gradle, travel to the project directory in terminal.
Then enter the command "gradle build" to build the application. Once build 
is successful, execute the "gradle run" command, and it will launch the
application.

To send file, use postman to send a post request to 
"http://localhost:9090/file/upload", along with the file attached as form
data. Post the request and on successful execution, the file will be 
aviailable on the bucket.

Below is a screenshot of postman request, for reference.

<img width="1282" alt="Screenshot 2022-01-16 at 4 04 01 PM" src="https://user-images.githubusercontent.com/97734839/149656524-d3ee3888-8352-4271-a4b1-6b86559a65a3.png">
