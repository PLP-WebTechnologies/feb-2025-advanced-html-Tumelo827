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
  <title>Business Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
    }
    table, th, td {
      border: 1px solid #ccc;
      border-collapse: collapse;
      padding: 8px;
    }
    th {
      background-color: #f2f2f2;
    }
    form {
      margin-top: 30px;
      max-width: 500px;
    }
    form input, form select {
      width: 100%;
      padding: 8px;
      margin: 6px 0 15px 0;
      box-sizing: border-box;
    }
    .form-section {
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <h1>Business Overview</h1>

  <!-- Ordered List with Roman Numerals -->
  <h2>Benefits</h2>
  <ol type="I">
    <li>Financial Freedom</li>
    <li>Flexible Working Hours</li>
    <li>Unlimited Income Potential</li>
    <li>Be Your Own Boss</li>
    <li>Legacy Creation</li>
  </ol>

  <!-- External Image from Pexels -->
  <h2>Inspiration</h2>
  <img src="https://images.pexels.com/photos/3184465/pexels-photo-3184465.jpeg" alt="Business Image" width="600">

  <!-- Contact Table -->
  <h2>Contact List</h2>
  <table>
    <tr>
      <th>Name</th>
      <th>Address</th>
      <th>Mobile</th>
      <th>Email</th>
    </tr>
    <tr>
      <td>John Doe</td>
      <td>123 Maple Street</td>
      <td>071-234-5678</td>
      <td>john@example.com</td>
    </tr>
    <tr>
      <td>Jane Smith</td>
      <td>456 Oak Avenue</td>
      <td>072-987-6543</td>
      <td>jane@example.com</td>
    </tr>
    <tr>
      <td>Thabo Mokoena</td>
      <td>789 Pine Road</td>
      <td>073-456-7890</td>
      <td>thabo@example.com</td>
    </tr>
    <tr>
      <td>Ayesha Khan</td>
      <td>321 Cedar Blvd</td>
      <td>074-123-4567</td>
      <td>ayesha@example.com</td>
    </tr>
    <tr>
      <td>Sipho Ndlovu</td>
      <td>159 Birch Lane</td>
      <td>075-789-1234</td>
      <td>sipho@example.com</td>
    </tr>
  </table>

  <!-- Registration Form -->
  <h2>Registration Form</h2>
  <form action="#" method="post">
    
    <!-- Name -->
    <div class="form-section">
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your full name" required>
    </div>

    <!-- Email -->
    <div class="form-section">
      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" placeholder="e.g., yourname@example.com" required>
    </div>

    <!-- Password -->
    <div class="form-section">
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6">
    </div>

    <!-- Date of Birth -->
    <div class="form-section">
      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required>
    </div>

    <!-- Dropdown (Interest Area) -->
    <div class="form-section">
      <label for="interest">Area of Interest:</label>
      <select id="interest" name="interest" required>
        <option value="">-- Please select --</option>
        <option value="sales">Sales</option>
        <option value="marketing">Marketing</option>
        <option value="tech">Technology</option>
        <option value="admin">Administration</option>
      </select>
    </div>

    <!-- Radio Buttons (Availability) -->
    <div class="form-section">
      <label>Availability:</label><br>
      <input type="radio" id="fulltime" name="availability" value="fulltime" required>
      <label for="fulltime">Full Time</label><br>
      <input type="radio" id="parttime" name="availability" value="parttime">
      <label for="parttime">Part Time</label>
    </div>

    <!-- Checkboxes (Skills) -->
    <div class="form-section">
      <label>Skills:</label><br>
      <input type="checkbox" id="communication" name="skills" value="communication">
      <label for="communication">Communication</label><br>
      <input type="checkbox" id="leadership" name="skills" value="leadership">
      <label for="leadership">Leadership</label><br>
      <input type="checkbox" id="teamwork" name="skills" value="teamwork">
      <label for="teamwork">Teamwork</label>
    </div>

    <!-- Submit Button -->
    <input type="submit" value="Register">

  </form>

</body>
</html>

