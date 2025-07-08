# Event_Invitation
## Date:08-07-2025
## Sachin B
## 212222060207
## Objective:

The objective of this project is to design and implement a visually appealing and user-friendly event invitation card using HTML and CSS.

## Tasks:

#### 1. Set Up the HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the basic structure.

Add an appropriate <title> such as "Event Invitation".

#### 2. Add Page Headings:

Insert a main heading using ```<h1>``` for the user's name.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Event Invitation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="invite-card">
        <img src="alumni.jpeg" alt="Event Banner" class="invite-image">
        <h1>Annual Alumni Meet</h1>
        <h3>Reconnect & Celebrate Together</h3>
        <div class="invite-details">
            <p><span class="label">Date:</span> December 25, 2025</p>
            <p><span class="label">Time:</span> 6:00 PM onwards</p>
            <p><span class="label">Venue:</span> College Auditorium</p>
        </div>
        <footer class="invite-footer">
            <p>RSVP: Sachin  &nbsp;|&nbsp; +91 7200006676 &nbsp;|&nbsp; <a href="#">alumni@sec.edu</a></p>
        </footer>
    </div>
</body>
</html>

```
## Output:
![Screenshot 2025-07-08 133906](https://github.com/user-attachments/assets/61721433-2a9f-484b-893b-04f033612a66)

## Css Code:
```
body {
    background-color: #f8f4ee;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
}

.invite-card {
    width: 360px;
    background: #fffdfa;
    padding: 2rem 2rem 1.5rem 2rem;
    border-radius: 18px;
    box-shadow: 0 6px 24px rgba(80, 60, 30, 0.08);
    margin: 48px auto 0 auto;
    text-align: center;
}

.invite-image {
    max-width: 100%;
    border-radius: 12px;
    display: block;
    margin: 0 auto 1.2rem auto;
}

h1 {
    color: #6b4f2c;
    margin-bottom: 0.4rem;
    font-size: 2rem;
    letter-spacing: 1px;
}

h3 {
    color: #a17b4b;
    margin-top: 0;
    margin-bottom: 1.3rem;
    font-weight: 500;
    font-size: 1.15rem;
}

.invite-details {
    margin-bottom: 1.5rem;
}

.invite-details p {
    margin: 0.3rem 0;
    font-size: 1rem;
    color: #55422b;
    text-align: left;
    padding-left: 18%;
}

.label {
    font-weight: bold;
    color: #8b5e2a;
    margin-right: 0.6em;
}

.invite-footer {
    border-top: 1px solid #f0e7d8;
    margin-top: 1.2rem;
    padding-top: 1rem;
    font-size: 0.97rem;
    color: #7a6a4d;
    background: #fcf8f3;
    border-radius: 0 0 14px 14px;
}

.invite-footer a {
    color: #a17b4b;
    text-decoration: none;
}

.invite-footer a:hover {
    text-decoration: underline;
}
```




## Result:

This structure ensures your invitation is clear, engaging, and contains all the necessary information for guests to respond and attend.
