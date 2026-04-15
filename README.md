<!DOCTYPE html>
<head>
<title>Summer Coats</title>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #fff;
    }

    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 50px;
    }

    /* LEFT SIDE */
    .text-section {
        max-width: 50%;
    }

    .text-section h1 {
        color: #f26522;
        font-size: 48px;
        margin: 0;
    }

    .text-section p {
        margin: 10px 0;
        color: #333;
    }

    .stars {
        color: black;
        font-size: 18px;
    }

    .btn {
        display: inline-block;
        margin-top: 20px;
        padding: 12px 40px;
        background: #f26522;
        border-radius: 25px;
        color: white;
        text-decoration: none;
        font-weight: bold;
    }

    /* RIGHT SIDE */
    .image-section {
        position: relative;
        width: 300px;
        height: 400px;
    }

    .circle {
        position: absolute;
        width: 250px;
        height: 250px;
        background: #f26522;
        border-radius: 50%;
        bottom: 0;
        right: 0;
    }

    .image-section img {
        position: absolute;
        width: 100%;
        height: auto;
        top: 0;
        right: 0;
        object-fit: cover;
    }

    /* NAV */
    .nav {
        display: flex;
        justify-content: center;
        gap: 30px;
        padding: 20px;
        font-size: 14px;
    }

    .nav a {
        text-decoration: none;
        color: black;
    }

    .nav a.active {
        color: #f26522;
        font-weight: bold;
    }
</style>
</head>

<body>

<!-- NAVIGATION -->
<div class="nav">
    <a href="new tab">OUTER</a>
    <a href="new tab">COAT</a>
    <a href="new tab" class="active">VEST</a>
    <a href="new tab">WAISTCOAT</a>
    <a href="new tab">BLAZER</a>
    <a href="new tab">FASHION</a>
</div>

<!-- MAIN SECTION -->
<div class="container">

    <!-- TEXT -->
    <div class="text-section">
        <h1>SUMMER COATS</h1>
        <p><strong>louve collection</strong></p>
        <p>size 56</p>

        <p><strong>NEW STOCK</strong></p>
        <div class="stars">★★★★★</div>

        <a href="new tab" class="btn"></a>
    </div>

    <!-- IMAGE -->
    <div class="image-section">
        <div class="circle"></div>
        <!-- Replace with your image -->
        <img src="C:\Users\ndind\Music\index.html/girl.jpg" class="small-model" alt="girl">
    </div>

</div>

</body>
</html>
