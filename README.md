# Ex.06 Book Front Cover Page Design
## Date: 08-10-2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
.book-cover {
  width: 600px;
  height: 900px;
  border: 4px solid red;
  display: flex;
  flex-direction: column;
  background: linear-gradient(180deg, orange, gold);
}

.top {
  flex: 2;
  padding: 30px;
  background: linear-gradient(180deg, #ff6600, #ffcc00);
  color: white;
}

.top h4 {
  margin: 0;
  font-size: 18px;
}

.title {
  margin-top: 40px;
  font-size: 42px;
  font-weight: bold;
  text-transform: uppercase;
}

.subtitle {
  margin-top: 20px;
  font-size: 22px;
}

.bottom {
  flex: 1;
  background: linear-gradient(180deg, gold, orange);
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: white;
}

.bottom-left {
  max-width: 70%;
}

.special {
  font-weight: bold;
  font-size: 20px;
}

.author {
  margin-top: 15px;
  font-size: 18px;
}

.bottom-right img {
  width: 100px;
  height: 120px;
  object-fit: cover;
  border: 2px solid white;
}

SEC Insights 
<div class="bottom">
  <div class="bottom-left">
    <div class="special">SPECIAL EDITION</div>
    <div class="author">Ms. Priyadharshini V </div>
  </div>
  <div class="bottom-right">
    <!-- Replace the src with your photo link -->
    <img src="![passport size photo](https://github.com/user-attachments/assets/c4387437-336d-46f3-8442-c48fd60e4ffc)
" alt="Author Photo">
  </div>
</div>

## OUTPUT:

![front cover ](https://github.com/user-attachments/assets/e8aec2e8-4901-4774-82b1-6a29b033e9ba)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
