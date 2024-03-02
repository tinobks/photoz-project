Application that allows me to upload, delete and download photos through a database.
I used Java 21 and Spring Boot with a few dependencies (like spring web for REST and h2database for SQL).
Thanks to @marcobehlerjetbrains for the tutorial.

After starting application, go to http://localhost:8080/upload.html to upload a pic from your PC. (You can add more pics and every pic will have own ID).
Go to localhost:8080/download/{id} to download an uploaded file.
