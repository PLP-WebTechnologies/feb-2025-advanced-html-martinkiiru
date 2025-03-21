ASSIGNMENT

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements and Forms</title>
</head>
<body>
    <header>
        <h1>HTML5 Elements and Forms</h1>
    </header>
    
    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
            <li>Fifth Item</li>
        </ol>
    </section>
    
    <!-- External Image -->
    <section>
        <h2>External Image</h2>
        <img src="https://images.pexels.com/photos/1366913/pexels-photo-1366913.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Sample Image from Pexels" width="600">
    </section>
    
    <!-- Contacts Table -->
    <section>
        <h2>Contact List</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Doe</td>
                    <td>123 Main St</td>
                    <td>+1234567890</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak Ave</td>
                    <td>+0987654321</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Mike Johnson</td>
                    <td>789 Pine Rd</td>
                    <td>+1112223333</td>
                    <td>mike@example.com</td>
                </tr>
                <tr>
                    <td>Lisa Brown</td>
                    <td>321 Elm St</td>
                    <td>+4445556666</td>
                    <td>lisa@example.com</td>
                </tr>
                <tr>
                    <td>Tom Wilson</td>
                    <td>987 Maple Dr</td>
                    <td>+7778889999</td>
                    <td>tom@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter password" required>
            <br>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br>
            
            <label for="gender">Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required> Male
            <input type="radio" id="female" name="gender" value="female" required> Female
            <br>
            
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select a country</option>
                <option value="india">India</option>
                <option value="usa">USA</option>
                <option value="uk">UK</option>
            </select>
            <br>
            
            <label>Interests:</label>
            <input type="checkbox" name="interests" value="sports"> Sports
            <input type="checkbox" name="interests" value="music"> Music
            <input type="checkbox" name="interests" value="reading"> Reading
            <br>
            
            <button type="submit">Register</button>
        </form>
    </section>
    
    <!-- Multimedia Elements -->
    <section>
        <h2>Multimedia</h2>
        <audio controls>
            <source src="254happiness.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        <br>
        <video width="600" controls>
            <source src="https://videos.pexels.com/video-files/31187306/13323002_360_640_60fps.mp4" type="video/mp4">
        </video>
    </section>
</body>
</html>


## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
