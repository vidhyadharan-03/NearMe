# Ex04 Places Around Me
## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Clone the github repository into Theia IDE.

### STEP 2
Create a new Django project

### STEP 3
Write the needed HTML code.

### STEP 4
Run the Django server and execute the HTML files.

### STEP 5
Execute the programs and publish them.

## CODE
```
map.html

<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Chennai-Captain of states</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>VIDHYADHARAN R (212222110053)</b></font>
</h3>
<center>
<img src="/static/images/mapnew.png" usemap="#MyCity" height="620" width="1200">
<map name="MyCity">
<area shape="circle" coords="1000,440,20" href="/static/html/hosptial.html" title="ESIC Hospial">
<area shape="rectangle" coords="450,160,700,100" href="/static/html/rto.html" title="RTO Office">
<area shape="circle" coords="585,250,52" href="/static/html/temple.html" title="Iyappan Temple">
<area shape="circle" coords="900,400,15" href="/static/html/bus.html" title="k.k.Nagar Bus Stand">
<area shape="rectangle" coords="940,160,880,130" href="/static/html/park.html" title="Sivan Park">
</map>
</center>
</body>
</html>

bus.html

<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Chennai-captain of states</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>K.K.NAGAR Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Chennai, formerly Madras, city, capital of Tamil Nadu state, southern India, located on the Coromandel Coast of the Bay of Bengal. Known as the “Gateway to South India,” Chennai is a major administrative and cultural centre.
 Pop. (2011) city, 4,646,732; urban agglom., 8,696,010.Chennai is located on the Coromandel Coast along the Bay of Bengal. The Cooum (Koovam) River flows through its centre and the Adyar River through its southern portion. 
 The Buckingham Canal runs parallel to the coast, joining the Kortalaiyar (Kosasthalaiyar) River in the northern edges of the city and the Muttukadu Backwaters south of the city.
 Chennai’s climate is warm and humid. It reaches average temperatures of 89 °F (32 °C) in May and 77 °F (25 °C) in January. Annual rainfall is about 50 inches (1,250 mm), occurring mostly from October to mid-December.
</b>
</font>
</p>
</body>
</html>

hosptial.html

<html lang="en">
<head>
<title>ESIC HOSPITAL</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>CHENNAI-Caption Of States</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ESIC HOSPITAL</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
ESIC -Employee's State Insurance Corporation, Ministry of Labour & Employment, Government of India.

ESI Hospital KK Nagar is one of the most well-known hospitals in this area for insured person (IP).
It is located on Anna Main Road in Chennai. Over the years, the practitioner has gained the immense faith for their services.
ESI Hospital KK Nagar is located Near Ashok Pillar, Peripheral Hospital, ESI Hospital Bus Stop, Anna Main Road, K K Nagar-600078.
It is close to all of these locations and is easy to reach by a number of transportation options.
</font>
</p>
</body>
</html>

park.html

<html lang="en">
<head>
<title>Sivan Park</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>CHENNAI-Caption Of States</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sivan Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
    Sivan Park is the most popular park and well known for its greater beauty.
    In Chennai there is no other place that is equivalently beautiful with a big statue of Lord Shiva meditating.
    In this way the Sivan park is unique in Chennai.

</font>
</p>
</body>
</html>

rto.html

<html lang="en">
<head>
<title>RTO Office</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>CHENNAI-Caption Of States</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>RTO Office</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
RTO office or the Regional Transport Office is a government body specifically established to oversee all transport-related operations in the country. RTOs are located throughout the country in each state and union territory. RTOs are responsible for enforcing the rules as laid down by the Motor Vehicle Act of 1988.
The department also maintains a database of all the vehicles operating in the country as well as issues licenses for drivers. Besides, the RTO office also collects road taxes, supervises pollution checks, and ensures the enforcement of all road transportation rules. If you own or drive a vehicle in India, you will need to visit the RTO to get your vehicle registered, obtain a driver’s license or renew your driver’s license, etc.
RTOs are also responsible for improving road and vehicle safety, especially to avoid accidents and other road fatalities.
</b>
</font>
</p>
</body>
</html>

temple.html

<html lang="en">
<head>
<title>Iyappan Temple</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>CHENNAI-Caption Of States</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Iyyapan temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
A nice place for worship. There are four Sannithis for Lord Ayyappan, Ganesa, Bhagavathi and Guruvaurappan. Peaceful atmosphere. 
Everyday morning 7.30 am there will be aarthi for Lord Ayyappan. So 7.15 am Ayyappan Sannidhi doors will be closed for aarthi at 7.30 am. Similarly at 6.45 pm in the evening for 7.00 pm aarthi.
 After Ayyappan aarthi in the evening 7.00 pm, there will be aarthi for Guruvaurappan followed by aarthi for Bhagavathi and then Lord Ganesa. 
</font>
</p>
</body>
</html>
```



## OUTPUT

![mapnew](https://github.com/vidhyadharan-03/NearMe/assets/114286357/676c7417-a7bd-474c-a22e-9f36f196e96b)

![bus_stand](https://github.com/vidhyadharan-03/NearMe/assets/114286357/74aab81d-e54a-47c8-b6b6-d43daf52ae2c)

![rto](https://github.com/vidhyadharan-03/NearMe/assets/114286357/b7985969-c3b5-4613-878a-e374156eb184)

![sivan](https://github.com/vidhyadharan-03/NearMe/assets/114286357/9cd7e7dc-83cb-4f36-b5ee-74fdeef50763)

![temple](https://github.com/vidhyadharan-03/NearMe/assets/114286357/ccb5027f-9de7-41b0-b41b-7871dc87bc7d)

![esic](https://github.com/vidhyadharan-03/NearMe/assets/114286357/430c5367-1a32-48fe-b2c2-a09ba75b5f60)


## HTML VALIDATOR

![validator](https://github.com/vidhyadharan-03/NearMe/assets/114286357/892ae908-462b-435f-b20a-b46fac6aa352)


## RESULT
The program for implementing image maps using HTML is executed successfully.
