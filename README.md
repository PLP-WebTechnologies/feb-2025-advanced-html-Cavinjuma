# Advanced HTML5 Elements and Forms

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
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Juma Cavin HTML5 registration</title>
</head>
<body>

    <h1>...Welcome to My WEB...</h1>

    <!-- Ordered with Roman numerals -->
    <h2>My Favorite Activities</h2>
    <ol type="I">
        <li>Reading Books</li>
        <li>Playing Football</li>
        <li>Traveling</li>
        <li>Coding Projects</li>
        <li>Photography</li>
    </ol>

    <!-- External image from pexels.com -->
    <h2>Beautiful Scenery</h2>
    <img src="https://images.pexels.com/photos/417173/pexels-photo-417173.jpeg" alt="Nature" width="600">

    <!-- Table of 5 contacts -->
    <h2>Contact List</h2>
    <table border="1" cellpadding="10" cellspacing="0">
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
                <td>John Kamau</td>
                <td>Koinange street</td>
                <td>0734567890</td>
                <td>john@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Atieno</td>
                <td>Kimathi street</td>
                <td>0987654321</td>
                <td>jane@gmail.com</td>
            </tr>
            <tr>
                <td>Mike Brown</td>
                <td>Waiyaki way</td>
                <td>0122334455</td>
                <td>mike@example.com</td>
            </tr>
            <tr>
                <td>Lisa Ntokwa</td>
                <td>Tom Mboya St</td>
                <td>0677889900</td>
                <td>lisa@gmail.com</td>
            </tr>
            <tr>
                <td>Tom Musyoka</td>
                <td>Westlands</td>
                <td>0566778899</td>
                <td>tom@gmail.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">

        <!-- Name -->
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

        <!-- Email -->
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password -->
        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

        <!-- Date of Birth -->
        <label for="dob">Date of Birth:</label><br>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown -->
        <label for="country">Select Country:</label><br>
        <select id="country" name="country" required>
            <option value="">--Select--</option>
            <option value="kenya">Kenya</option>
            <option value="uganda">Uganda</option>
            <option value="tanzania">Tanzania</option>
        </select><br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label><br>

        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label><br><br>

        <!-- Checkboxes -->
        <label>Interests:</label><br>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label><br>

        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label><br>

        <input type="checkbox" id="travel" name="interests" value="travel">
        <label for="travel">Travel</label><br><br>

        <!-- Submit Button -->
        <input type="submit" value="Register">
        <input type="reset" value="Reset All">

    </form>

</body>
</html>
