# Exp--9-Create-a-Birthday-card-using-HTML-and-CSS

## AIM:
To create a birthday card using HTML and CSS.

## ALGORITHM: 
### Step 1:
Determine the look and style of the birthday card you want to create.
### Step 2: 
Develop a HTML code to create the birthday card.
### Step 3: 
Add background colors and images and decorate your card using CSS.
### Step 4: 
Link your CSS to the HTML file.
### Step 5:  
Using Live Server display the result.

## PROGRAM:
### HTML:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="bday.css">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap">
  <title>Birthday card</title>
</head>
<body>
  <div class="card">
    <img src="https://cdn.pixabay.com/photo/2020/10/06/21/54/cake-5633461__480.png" alt="birthday" class="birthday">
    <div class="text">
      <h1>Happy Birthday!</h1>
      <p>Have a great future..!</p>
    
      <div class="credit">Made with <span style="color:tomato">❤</span> by H.Syed Abdul Wasih</div>
    </div>
    <div class="space"></div>
  </div>
</body>
</html>

~~~
### CSS:
~~~

* {
  transition: all 0.2s ease-in-out;
}

body {
  background: #DCE35B; 
background: -webkit-linear-gradient(to right, #949398FF, #F4DF4EFF); 
background: linear-gradient(to right, #949398FF, #F4DF4EFF); 
  display: grid;
  place-items: center;
  height: 100vh;
  margin: 0;
  font-family: 'Open Sans', sans-serif;
}

.card {
  background: #12192c;
  border-radius: 30px;
  height: 85vh;
  width: 80vw;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 1em;
  overflow: hidden;
  color:#DCE35B;
}

@media only screen and (min-width: 1000px) {
  .card {
    flex-direction: row-reverse;
  }
  .card img.birthday {
    width: 60%;
    max-width: 50vw;
    max-height: unset;
    border-radius: 30px;
  }
}

@media only screen and (max-height: 640px) {
  .card {
    flex-direction: row-reverse;
  }
  .card img.birthday {
    width: 100%;
    max-width: 50vw;
    max-height: unset;
  }
}

img.birthday {
  max-height: 40vh;
  box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
}

.text {
  padding: 3em;
}
.text h1{
  font-family:cursive;
  font-size: 40px;
}
.space {
  height: 100px;
}

.credit a{
  text-decoration: none;
  color: #fff;
}

.credit {
    margin-top: 10px;
    text-align: center;
}


~~~
## OUTPUT:
![bday](https://github.com/abdulwasih2003/Exp--9-Create-a-Birthday-card-using-HTML-and-CSS/assets/91781810/ac19baca-6c9b-4138-98c4-5d5892631d2a)


## RESULT:
Thus to create a birthday card using HTML and CSS is successful.



