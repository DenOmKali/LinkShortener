---
# Github url shortener
***
### Back-end url shortener Rest API on Java
> In order to shorten a link you need to do these things:
>>1. Download the archive on github and extract it;
>>2. Launch the development environment, I have it IntelIJ IDEA;
>>3. Open unpacked project in development environment: 

![](/screenshots/1screen.png)

>>4. Load dependencies from pom.xml file
>>5. Start project:

![](/screenshots/2screen.png)

>>6. Log in using the link https://localhost:8080 and fill in the authorization fields:
>>login: user, password: 54321

![](/screenshots/3screen.png)

>>7. Login to postman and create POST request with JSON file
>>Enter http://localhost:8080/ in the request field
>>in the JSON file in the "url" field, write the link and click Send

![](/screenshots/4screen.png)

>>8. Next, to our link http://localhost:8080/ we add the alias that we wrote, this is a test for me
>>We go into the browser and write our link in full with the added alias http://localhost:8080/test
>>Next, we are already redirected to the link that we specified in the JSON file:

![](/screenshots/5screen.png)
 
 ###Have a good day)