# Parralex-design
A Parallax design for shaping my skills and also some parts which have professional looks. I think It was an amazing practice set?
# 👋 Welcome to Parralex Design

> Made with ❤️ by [Abbasi Codes Hub](https://github.com/Abbasi-codes-hub)

---

## 🔥 Live Typing Effect Preview (HTML + CSS)

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="../html/src/css/style.css">
</head>

<body>
    <section class="section-1">
        <h2>Welcome On Board</h2>
        <p>Embark on a journey where your vision turns into reality.</p>
    </section>

    <section class="section-2">
        <h2>Our Mission</h2>
        <p>We aim to deliver excellence with every line of code.</p>
    </section>

    <section class="section-3">
        <h2>Crafted With Passion</h2>
        <p>Every project reflects our dedication and attention to detail.</p>
    </section>

    <section class="section-4">
        <h2>Innovation At Core</h2>
        <p>We embrace the latest technologies to stay ahead of the curve.</p>
    </section>

    <section class="section-5">
        <h2>Client-Centric Approach</h2>
        <p>Your satisfaction is not just a goal; it’s our priority.</p>
    </section>

    <section class="section-6">
        <h2>Let’s Build Together</h2>
        <p>Join hands and let’s create something extraordinary.</p>
    </section>

</body>
</html>

                    ...........CSS.............

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    min-height: 100vh;
    width: 100vw;
    font-family: cursive;
    color: rgb(255, 179, 0);
    overflow-x: hidden;
}

h2 {
    font-size: 3rem;
    font-weight: 700;
    font-family: fantasy;
    text-transform: uppercase;
    letter-spacing: 2px;
    text-shadow: 2px 2px 5px black;
    margin: 0;
    padding: 0;
}

p {
    font-size: 20px;
    color: rgb(234, 249, 13);
    padding: 1rem 2rem;
}

/* Common Section Class */
section {
    width: 100%;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
    background-repeat: no-repeat;
}

/* Now individual sections with images and gradients */

.section-1 {
    background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
        url("https://plus.unsplash.com/premium_photo-1727073934900-72c54217a20b?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8YXN0aGV0aWMlMjBwaWN0dXJlcyUyMGxhbmRzY2FwZSUyMHdlYiUyMGRldmVsb3BlcnxlbnwwfHwwfHx8MA%3D%3D");
}

.section-2 {
    background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
        url("https://images.unsplash.com/photo-1621857093087-7daa85ab14a6?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8d2ViJTIwZGV2ZWxvcGVyfGVufDB8fDB8fHww");
}

.section-3 {
    background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
        url("https://plus.unsplash.com/premium_photo-1675793715030-0584c8ec4a13?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8d2ViJTIwZGV2ZWxvcGVyfGVufDB8fDB8fHww");
}

.section-4 {
    background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
        url("https://plus.unsplash.com/premium_photo-1663040543387-cb7c78c4f012?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTN8fHdlYiUyMGRldmVsb3BlcnxlbnwwfHwwfHx8MA%3D%3D");
}

.section-5 {
    background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
        url("https://images.unsplash.com/photo-1623479322729-28b25c16b011?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTZ8fHdlYiUyMGRldmVsb3BlcnxlbnwwfHwwfHx8MA%3D%3D");
}

.section-6 {
    background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
        url("https://images.unsplash.com/photo-1467232004584-a241de8bcf5d?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjB8fHdlYiUyMGRldmVsb3BlcnxlbnwwfHwwfHx8MA%3D%3D");
}
