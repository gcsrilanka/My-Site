<html>
<head>
    <title>Contact Form</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <div class="contact-title">
       <h1>Say Hello</h1> 
       <h2>We are always ready to serve you.....</h2>
    </div>
    <div class="contact-form">
        <form id="contact-form" method="post" action="contact-form-handler ">
            <input name="name" type="text" class="form-control" placeholder="your name" required>
            <br>
            <input name="email" type="email" class="form-control" placeholder="your email" required>
            <br>
            <textarea name="Message" class="form-control" placeholder="Message" row="4" required></textarea><br>
            <input type="submit" class="form-control submit" value="SEND MESSAGE">
        </form>
    </div>
</body>
</html>