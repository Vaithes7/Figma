# Ex09 Event Registration Web Application
# Date: 25.11.2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
HOME PAGE
```
<div style="width: 390px; margin: 0 auto; font-family: Arial, sans-serif; text-align: center; border: 1px solid #ddd; border-radius: 20px; overflow: hidden; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);">
  <div style="background-color: #fff; padding: 10px;">
    <img src="/mnt/data/Screenshot%202024-12-20%20223450.png" alt="Saveetha Logo" style="width: 100%; margin-bottom: 10px;">
  </div>
  <div style="padding: 20px; background: linear-gradient(135deg, #f0f0f0, #ffffff);">
    <h1 style="font-size: 22px; color: #0071bc; margin-bottom: 15px;">SPORTS DAY EVENTS</h1>
    <button style="display: block; width: 80%; margin: 10px auto; padding: 10px; background-color: #00bfff; color: white; border: none; border-radius: 5px; font-size: 16px; cursor: pointer;">LOGIN</button>
    <button style="display: block; width: 80%; margin: 10px auto; padding: 10px; background-color: #00bfff; color: white; border: none; border-radius: 5px; font-size: 16px; cursor: pointer;">REGISTER</button>
  </div>
  <div style="padding: 10px; font-size: 14px; color: #555;">
    <em>BORN TO WIN</em>
  </div>
</div>

```

EVENT PAGE
```
<div style="width: 390px; margin: 0 auto; font-family: Arial, sans-serif; text-align: center; border: 1px solid #ddd; border-radius: 20px; overflow: hidden; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);">
    <div style="background-color: #fff; padding: 10px;">
      <img src="/mnt/data/Screenshot%202024-12-20%20223503.png" alt="Sports Day Events" style="width: 100%; margin-bottom: 10px;">
    </div>
    <div style="padding: 20px; background: #fff;">
      <h1 style="font-size: 22px; color: #0071bc; margin-bottom: 15px;">SPORTS DAY EVENTS</h1>
      <ul style="list-style-type: none; padding: 0; font-size: 18px; color: #333; text-align: left;">
        <li>1. FOOTBALL</li>
        <li>2. CRICKET</li>
        <li>3. BADMINTON</li>
        <li>4. KABADDI</li>
        <li>5. 100 MTS</li>
        <li>6. 200 MTS</li>
        <li>7. 800 MTS</li>
      </ul>
    </div>
  </div>
```

REGISTRATION PAGE
```
<div style="width: 390px; margin: 0 auto; font-family: Arial, sans-serif; text-align: center; border: 1px solid #ddd; border-radius: 20px; overflow: hidden; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); background: #fff;">
  <div style="background-color: #fff; padding: 10px;">
    <img src="/mnt/data/Screenshot%202024-12-20%20223512.png" alt="Event Registration Form" style="width: 100%; margin-bottom: 10px;">
  </div>
  <div style="padding: 20px; text-align: left; font-size: 16px;">
    <h1 style="text-align: center; font-size: 22px; color: #d300d3; margin-bottom: 10px;">EVENT REGISTRATION FORM</h1>
    <p style="font-weight: bold; text-align: center; margin-bottom: 20px;">Fill the details</p>
    <form>
      <input type="text" placeholder="Full Name" style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;">
      <input type="text" placeholder="Gender" style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;">
      <input type="number" placeholder="Age" style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;">
      <input type="text" placeholder="Register Number" style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;">
      <input type="text" placeholder="Department" style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;">
      <input type="text" placeholder="Mobile Number" style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;">
      <input type="email" placeholder="Email ID" style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;">
      <input type="text" placeholder="Events To Register" style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;">
      <button type="submit" style="width: 100%; padding: 10px; background-color: #00bfff; color: white; border: none; border-radius: 5px; font-size: 16px; cursor: pointer;">REGISTER</button>
    </form>
  </div>
</div>
```

CONTACT US 
```
<div style="width: 390px; margin: 0 auto; font-family: Arial, sans-serif; text-align: center; border: 1px solid #ddd; border-radius: 20px; overflow: hidden; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);">

  <img src="your-image-url.jpg" alt="Saveetha College" style="width: 100%; border-bottom: 1px solid #ddd;">
  <div style="background: linear-gradient(135deg, #cce7ff, #ffffff); padding: 30px; box-sizing: border-box;">
    <h1 style="font-size: 24px; color: #000; margin-bottom: 10px;">THANK YOU</h1>
    <p style="font-size: 18px; color: #444; margin-bottom: 20px;">We are all eagerly waiting for your participation in the sports events</p>
    <div style="font-size: 20px; font-weight: bold; color: #00c700; margin-bottom: 10px;">CONTACT US</div>
    <p style="font-size: 16px; color: #555; margin: 0;">E-mail</p>
    <p style="font-size: 16px; color: #555; margin: 0;">saveethaengineeringcollege@gmail.com</p>
    <p style="font-size: 16px; color: #555;">Phone<br>6978697878<br>8487898737</p>
  </div>
</div>
```

# OUTPUT:

![Screenshot (62)](https://github.com/user-attachments/assets/6c2ada02-81b1-4702-9776-8c30962e7174)


HOME PAGE

![Screenshot 2024-12-20 223450](https://github.com/user-attachments/assets/a5589a65-36b7-43b4-b63f-4d3e136719d6)

EVENT PAGE

![Screenshot 2024-12-20 223503](https://github.com/user-attachments/assets/24565f0b-c6d6-4b54-99db-82c966b489af)

REGISTRATION PAGE

![Screenshot 2024-12-20 223512](https://github.com/user-attachments/assets/00d4719a-1b29-43f5-a344-9654c87b18d8)


CONTANCT US

![Screenshot 2024-12-20 223519](https://github.com/user-attachments/assets/8025cf03-6c60-476b-8344-f510f88d8313)









# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
