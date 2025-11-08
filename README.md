# Ex04 Places Around Me
## Date: 08-11-25

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1

Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
map.html

<!DOCTYPE html>
<html>
<head>
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>NAMAKKAL</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>BHARANIKA (24901181)</b></font>
</h2>
<center>    
<img src="map.png" usemap="#image-map">"#My city" height="800" width="1500">

<map name="My city">
    <area target="_blank" alt="" title="" href="malaikottai.html" coords="803,257,972,363" shape="rect">
    <area target="_blank" alt="" title="" href="restaurant.html" coords="221,81,445,172" shape="rect">
    <area target="_blank" alt="" title="" href="lake.html" coords="1553,15,1710,181" shape="rect">
    <area target="_blank" alt="" title="" href="school.html" coords="827,649,1135,761" shape="rect">
    <area target="_blank" alt="" title="" href="residency.html" coords="432,595,646,714" shape="rect">
</map>
</center>
</body>
</html>

malaikottai.html

<html>
    <body bgcolor="grey">
        <h1 align="center">
         <font color="blue"><b>NAMAKKAL</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>malaikottai</b>
        </h3>
        <hr size="5" color="red">
        <p font color="black">Namakkal Malai Kottai, also known as Namakkal Fort, is a majestic hill fort located in Namakkal, Tamil Nadu. Built on a massive single rock around the 17th century, it stands about 75 meters high and offers a breathtaking view of the surrounding town. The fort is believed to have been constructed by the Madurai Nayaks and later occupied by Tipu Sultan and the British. Within the fort, there are ancient temples dedicated to Lord Narasimha and Ranganayaki Thayar. Malai Kottai is not only an architectural wonder but also a symbol of Namakkal’s rich history, culture, and Tamil heritage.</p>
        
    </body>
</html>

restaurant.html

<html>
    <body bgcolor="cyan">
        <h1 align="center">
         <font color="blue"><b>NAMAKKAL</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>restaurant</b>
        </h3>
        <hr size="3" color="rose">
        <p font color="black">Table Tree Family Restaurant is a well-known dining place in Namakkal, Tamil Nadu, located on Madurai Veeran Pudur New Road. It offers a variety of South Indian, North Indian, and Chinese dishes, including favorites like Butter Naan, Chicken 65, and Mushroom Masala. The restaurant is appreciated for its pleasant ambience, neat surroundings, and family-friendly atmosphere. With reasonable prices and good service, it is a popular choice for both locals and visitors. Table Tree Restaurant provides dine-in, takeaway, and delivery options, making it a convenient spot for enjoying delicious food in a comfortable and welcoming environment.</p>
        
    </body>
</html>

lake.html

<html>
    <body bgcolor="orange">
        <h1 align="center">
         <font color="blue"><b>NAMAKKAL</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>lake</b>
        </h3>
        <hr size="3" color="green">
        <p font color="black">Namakkal Lake is a beautiful and serene water body located in the heart of Namakkal town, Tamil Nadu. Surrounded by lush greenery and walking paths, it serves as a popular spot for relaxation and recreation. The lake enhances the town’s natural beauty and supports local biodiversity. During evenings, it becomes a peaceful gathering place for families and visitors. The nearby Namakkal Fort adds to its scenic charm, reflecting beautifully on the lake’s surface. Efforts have been made to maintain its cleanliness and preserve its ecosystem, making Namakkal Lake both a tourist attraction and a vital part of the town’s environment.</p>
    </body>
</html>

school.html

<html>
    <body bgcolor="yellow">
        <h1 align="center">
         <font color="blue"><b>NAMAKKAL</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>school</b>
            </h3>
        <hr size="3" color="red">
        <p font color="black">Government Boys Higher Secondary School, Namakkal (South), is one of the oldest and most reputed educational institutions in Namakkal, Tamil Nadu. Established in 1891, it provides education from classes 6 to 12 under the Tamil Nadu State Board syllabus. The school focuses on academic excellence, discipline, and overall student development. It has well-equipped classrooms, computer labs, a library with over 18,000 books, and a large playground. The medium of instruction is Tamil, and English is also taught effectively. The school aims to provide quality education for all students and continues to produce many successful scholars and professionals every year.</p>
    </body>
</html>

residency.html

<html>
    <body bgcolor="green">
        <h1 align="center">
         <font color="blue"><b>NAMAKKAL</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>residency</b>
        </h3>
        <hr size="3" color="yellow">
        <p font color="black">Aswin Residency is a popular 3-star hotel located near the Fire Station on Periyapatty Main Road in Namakkal, Tamil Nadu. It offers 42 spacious, air-conditioned rooms equipped with comfortable bedding, modern bathrooms, and essential amenities like Wi-Fi and room service. The hotel provides free parking, 24-hour front desk service, and daily housekeeping. Known for its clean environment and friendly staff, Aswin Residency is ideal for both business and family stays. Its convenient location near famous landmarks such as the Namakkal Fort and Sri Anjaneyar Temple makes it a perfect choice for tourists visiting the historical town of Namakkal.</p>
        
    </body>
</html>



## OUTPUT 
<img width="1713" height="778" alt="map" src="https://github.com/user-attachments/assets/80e417f3-5a35-45e5-b3f5-70cb9275cd41" />

<img width="876" height="387" alt="Screenshot 2025-10-08 212036" src="https://github.com/user-attachments/assets/4481743f-edbd-4f27-91b5-7a7ce042b024" />

<img width="881" height="365" alt="Screenshot 2025-10-08 212110" src="https://github.com/user-attachments/assets/197c503f-0b18-4e4a-a6e1-5410d25f3927" />

<img width="876" height="373" alt="Screenshot 2025-10-08 211722" src="https://github.com/user-attachments/assets/bb09cf3c-3969-470e-abf5-dbdbfa220de0" />

<img width="875" height="367" alt="Screenshot 2025-10-08 211940" src="https://github.com/user-attachments/assets/8e1774f1-fe42-4ee4-8adc-fed8b917c14c" />


<img width="873" height="350" alt="Screenshot 2025-10-08 211859" src="https://github.com/user-attachments/assets/59dae6ec-24e5-4a11-b377-12657a3e043d" />










## RESULT
The program for implementing image maps using HTML is executed successfully.
