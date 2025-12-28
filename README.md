# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Creative Workshop Registration</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Merriweather:wght@700&display=swap" rel="stylesheet">

<style>
    :root{
        --main: #4e9eff;
        --dark: #0e1c35;
        --light: #ffffffd9;
    }

    body{
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background: linear-gradient(rgba(0,0,0,.4),rgba(0,0,0,.4)),
                    url('https://images.unsplash.com/photo-1521737604893-d14cc237f11d?auto=format&fit=crop&w=1950&q=80') no-repeat center/cover;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        color: #fff;
    }

    .box{
        background: rgba(255,255,255,.13);
        backdrop-filter: blur(10px);
        border-radius: 15px;
        padding: 35px;
        width: 95%;
        max-width: 450px;
        box-shadow: 0 10px 30px rgba(0,0,0,.3);
    }

    h2{
        text-align: center;
        margin-bottom: 10px;
        font-family: 'Merriweather', serif;
        font-size: 1.8rem;
    }

    p{
        text-align: center;
        margin-bottom: 25px;
        font-size: .9rem;
        opacity: .9;
    }

    label{
        font-size: .85rem;
        font-weight: 600;
        display: block;
        margin-bottom: 5px;
        color: #eaeaea;
    }

    input, select, textarea{
        width: 100%;
        padding: 12px;
        margin-bottom: 18px;
        border-radius: 8px;
        border: none;
        outline: none;
        font-size: .95rem;
        background: rgba(255,255,255,.9);
    }

    textarea{
        resize: none;
        height: 70px;
    }

    button{
    #    width: 100%;
    #    padding: 14px;
        border: none;
        cursor: pointer;
        background: var(--main);
        color: white;
        font-weight: 600;
        border-radius: 8px;
        font-size: 1rem;
        transition: .3s;
    }

    button:hover{
        background: var(--dark);
    }

    .tag{
        text-align: center;
        font-size: .7rem;
        margin-top: 12px;
        opacity: .7;
    }
</style>
</head>
<body>

<div class="box">
    <h2>Creative Workshop Sign-Up</h2>
    <p>Join our hands-on design workshop and enhance your creativity.</p>

    <form>
        <label>Full Name</label>
        <input type="text" placeholder="Enter your name" required>

        <label>Email Address</label>
        <input type="email" placeholder="example@gmail.com" required>

        <label>Workshop Type</label>
        <select required>
            <option value="">Select Workshop</option>
            <option>Photography & Editing</option>
            <option>UI/UX Design</option>
            <option>Creative Writing</option>
            <option>3D Art & Animation</option>
        </select>

        <label>Experience Level</label>
        <select>
            <option>Beginner</option>
            <option>Intermediate</option>
            <option>Advanced</option>
        </select>

        <label>Short Note (Optional)</label>
        <textarea placeholder="Why do you want to join?"></textarea>

        <button type="submit">Register Now</button>
    </form>

    <div class="tag">Creativity starts with curiosity.</div>
</div>

</body>
</html>


## OUTPUT:
<img width="1041" height="548" alt="Screenshot 2025-12-28 194354" src="https://github.com/user-attachments/assets/0e2abb64-56d7-4970-ae61-b561a9fbe36a" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
