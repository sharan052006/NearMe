# Ex04 Places Around Me
## Date: 

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
```
map.html

<html>
    <head>
        <title>
        Madurai Goripalayam
        </title>
    </head>

    <body>
        <h1 align="left" style="background-color: pink;font-weight: inherit;font-style: inherit;font-family: 'Courier New', Courier, monospace;">
            GORIPALAYAM
        </h1>
        <h3 align="left" style="font-family: 'Courier New', Courier, monospace;font-size: small; color: blue;">
            SHARAN 24010956
        </h3>
        <img src="map.png" usemap="#MyCity" height="880" width="1354">
        <img src="map.png" usemap="#image-map">

        <map name="MyCity">
    <area target="" alt="RAJAJI PARK" title="RAJAJI PARK" href="park.html" coords="459,433,603,518" shape="rect">
    <area target="" alt="GANDHI MEMORIAL" title="GANDHI MEMORIAL" href="memorial.html" coords="774,370,952,488" shape="rect">
    <area target="" alt="THAMIZH SANGAM" title="THAMIZH SANGAM" href="sangam.html" coords="756,23,984,98" shape="rect">
    <area target="" alt="MEDICAL COLLEGE" title="MEDICAL COLLEGE" href="college.html" coords="500,556,754,634" shape="rect">
    <area target="" alt="CONVENTION CENTRE" title="CONVENTION CENTRE" href="ccentre.html" coords="211,242,453,356" shape="rect">
        </map>

    </body>
</html>

ccentre.html
<html>
<head>
    <title>Tamukkam Convention Center - Madurai</title>
</head>
<body style="background-color: #ffffff; text-align: center; font-family: Arial, sans-serif; color: #333333;">
    <h1 style="color: #ffffff; background-color: #009688; padding: 15px;">Tamukkam Convention Center - Madurai</h1>
    
    <h2 style="color: #ffffff; background-color: #00796b; padding: 10px;">About Tamukkam Convention Center</h2>
    <p style="font-size: 16px; line-height: 1.6; padding: 10px;">
        The Tamukkam Convention Center, located in the heart of Madurai, is a prestigious venue for hosting a variety of events including conferences, cultural programs, exhibitions, and weddings. With its large halls and modern facilities, the center is equipped to accommodate large gatherings and provide a platform for various activities.
    </p>
    
    <p style="font-size: 16px; line-height: 1.6; padding: 10px;">
        The convention center is well-known for its state-of-the-art infrastructure, offering a spacious auditorium, meeting rooms, and a fully equipped exhibition space. It is a popular choice for both corporate and social events in Madurai due to its central location and versatile event spaces.
    </p>

    <p style="font-size: 16px; line-height: 1.6; padding: 10px;">
        Tamukkam Convention Center also boasts an expansive parking area, excellent catering services, and is easily accessible for attendees from various parts of the city. The center’s design blends modern architecture with traditional elements, creating a unique ambiance for all types of events.
    </p>

    <p style="font-size: 16px; line-height: 1.6; padding: 10px;">
        Over the years, it has hosted several prominent events, including educational conferences, corporate seminars, cultural performances, and government functions. Tamukkam Convention Center has earned a reputation as one of the best venues in Madurai for hosting high-profile and memorable events.
    </p>

    <h2 style="color: #ffffff; background-color: #00796b; padding: 10px;">History of Tamukkam Convention Center</h2>
    <p style="font-size: 16px; line-height: 1.6; padding: 10px;">
        Tamukkam Convention Center was built with the vision of providing a dedicated space for cultural and professional events in Madurai. Over the years, it has transformed into one of the most popular venues in the city, known for its versatility and spacious design. 
    </p>

    <p style="font-size: 16px; line-height: 1.6; padding: 10px;">
        The convention center was originally conceived to serve as a hub for various local cultural activities, including theater, music, and dance performances. However, due to increasing demand for large-scale events, it was soon expanded to include modern facilities capable of hosting conferences, exhibitions, and seminars.
    </p>

    <p style="font-size: 16px; line-height: 1.6; padding: 10px;">
        Its rich history is intertwined with the growth of Madurai itself, as the city developed into a cultural and business center in South India. The convention center has played a key role in hosting several historical events and has been a witness to significant social, cultural, and political changes in the region.
    </p>

</body>
</html>

college.html

<html>
<head>
    <title>Madurai Medical College</title>
</head>
<body style="text-align: center;">
    <h1 style="color: darkblue; background-color: lightgray; padding: 10px;">Madurai Medical College</h1>
    
    <h2 style="color: darkgreen; background-color: lightyellow; padding: 5px;">About the College</h2>
    <p>Madurai Medical College, located in the city of Madurai, Tamil Nadu, is one of the premier medical institutions in India. Established in 1954, it has been a center for excellence in medical education and research.</p>
    
    <h2 style="color: darkgreen; background-color: lightyellow;">Key Features</h2>
    <ul>
        <li>State-of-the-art facilities and laboratories</li>
        <li>Highly experienced faculty members</li>
        <li>Affiliated with the Tamil Nadu Dr. M.G.R. Medical University</li>
        <li>Offers undergraduate and postgraduate medical courses</li>
        <li>Attached to the Government Rajaji Hospital for practical training</li>
    </ul>
    
    <h2 style="color: darkgreen; background-color: lightyellow; padding: 5px;">Contact Information</h2>
    <p>
        <strong>Address:</strong> Panagal Road, Alwarpuram, Madurai - 625020, Tamil Nadu, India <br>
        <strong>Phone:</strong> +91-452-2530923 <br>
    </p>
</body>
</html>

sangam.html

<html>
<head>
    <title>Tamil Sangam - Madurai</title>
</head>
<body style="background-color: #f4f4f4; text-align: center; font-family: Arial, sans-serif;">
    <h1 style="color: #5c4033; background-color: #d4b09c; padding: 15px;">Tamil Sangam - Madurai</h1>
    
    <h2 style="color: #0956f1; background-color: #f2c79c; padding: 10px;">About Tamil Sangam</h2>
    <p style="color: #ec0c0c; font-size: 16px; line-height: 1.6; padding: 10px;">
        Tamil Sangam, established in Madurai in the 19th century, is one of the oldest cultural organizations dedicated to preserving and promoting Tamil language, literature, and culture. It was formed with the objective of fostering a deeper understanding of Tamil heritage and to provide a platform for scholars, writers, and enthusiasts of Tamil literature to come together and share knowledge.
    </p>
    
    <p style="color: #11e3ee; font-size: 16px; line-height: 1.6; padding: 10px;">
        Over the years, Tamil Sangam has played a pivotal role in the cultural development of Tamil Nadu. It has hosted numerous literary events, conferences, and cultural programs aimed at reviving the Tamil literary tradition. The Sangam's library houses a vast collection of ancient Tamil texts, manuscripts, and modern works that contribute to the study and promotion of Tamil literature.
    </p>

    <p style="color: #e508c7; font-size: 16px; line-height: 1.6; padding: 10px;">
        Tamil Sangam also serves as a hub for Tamil cultural activities, including dance, music, and art forms that are intrinsic to Tamil Nadu’s rich cultural history. It continues to support and encourage the younger generation to embrace their roots through educational programs, exhibitions, and workshops.
    </p>

    <p style="color: #0ef325; font-size: 16px; line-height: 1.6; padding: 10px;">
        The organization has been at the forefront of promoting Tamil as a classical language, ensuring its preservation and growth through various initiatives. Tamil Sangam is a beacon for all things Tamil, striving to instill pride in the community and share the beauty of Tamil culture with the world.
    </p>
    
</body>
</html>

memorial.html

<html>
<head>
    <title>Gandhi Memorial Museum - Madurai</title>
</head>
<body style="background-color: beige; text-align: center; font-family: Arial, sans-serif;">
    <h1 style="color: darkgreen; background-color: lightyellow; padding: 15px;">Gandhi Memorial Museum - Madurai</h1>
    
    <h2 style="color: darkblue; background-color: lightblue; padding: 10px;">About the Museum</h2>
    <p style="color: black; font-size: 16px; line-height: 1.6; padding: 10px;">
        The Gandhi Memorial Museum in Madurai is a prominent landmark dedicated to the life and teachings of Mahatma Gandhi. Situated in the historic Tamukkam Palace, the museum was inaugurated in 1959 and is one of the largest museums dedicated to Gandhi in India. The museum's mission is to showcase the values of non-violence, truth, and peace that Gandhiji promoted throughout his life.
    </p>
    
    <p style="color: black; font-size: 16px; line-height: 1.6; padding: 10px;">
        The museum is home to an impressive collection of Gandhi's personal belongings, photographs, and documents from the Indian independence struggle. It also houses a large collection of rare artifacts, including letters, books, and manuscripts that highlight Gandhi’s interactions with other leaders and his philosophical writings.
    </p>

    <p style="color: black; font-size: 16px; line-height: 1.6; padding: 10px;">
        Visitors can explore various sections of the museum, each reflecting different phases of Gandhiji’s life, from his time in South Africa to his leadership in India's freedom movement. The museum aims to preserve his legacy and educate visitors about his profound impact on the nation and the world.
    </p>
    
    <p style="color: black; font-size: 16px; line-height: 1.6; padding: 10px;">
        The museum also offers educational programs for students, teachers, and general visitors, making it a significant spot for learning about India's freedom struggle and Gandhian philosophy. The building itself, with its architectural beauty, adds a historical charm to the entire experience.
    </p>
    
</body>
</html>


park.html

<html>
<head>
    <title>Rajaji Park - Madurai</title>
</head>
<body style="background-color: #2196F3; text-align: center; font-family: Arial, sans-serif;">
    <h1 style="color: white; background-color: #4CAF50; padding: 15px;">Rajaji Park - Madurai</h1>
    
    <h2 style="color: white; background-color: #388E3C; padding: 10px;">About Rajaji Park</h2>
    <p style="color: white; font-size: 16px; line-height: 1.6; padding: 10px;">
        Rajaji Park is a serene and scenic park located in the heart of Madurai. It is named after C. Rajagopalachari, an eminent leader, and serves as a major recreational hub for locals and tourists alike. The park is known for its lush greenery, well-maintained walking paths, and a variety of plant species, making it a peaceful retreat in the bustling city of Madurai.
    </p>
    
    <p style="color: white; font-size: 16px; line-height: 1.6; padding: 10px;">
        The park spans several acres and is home to a diverse range of flora and fauna. It features various sections, including well-manicured gardens, play areas for children, and ample spaces for jogging and exercise. Rajaji Park is often a favorite spot for morning walkers, families, and nature enthusiasts who enjoy its tranquil ambiance.
    </p>

    <p style="color: white; font-size: 16px; line-height: 1.6; padding: 10px;">
        Besides being a green space, Rajaji Park also serves as a venue for cultural events and public gatherings. Visitors can often enjoy local performances, festivals, and community activities that highlight the region’s rich cultural heritage. The park is well-known for its peaceful atmosphere, making it a perfect place for relaxation and stress relief.
    </p>

    <p style="color: white; font-size: 16px; line-height: 1.6; padding: 10px;">
        Rajaji Park is also equipped with basic amenities, including seating areas, drinking water, and a few food vendors around the park. It has become an essential part of the local community, providing a beautiful escape for anyone seeking solace in the midst of a busy city life.
    </p>
    
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (20).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
