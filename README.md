# WeddingInvite
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Georgia", serif;
}

:root {
    --burgundy: #800020;
    --dark-burgundy: #5c0017;
    --champagne-gold: #D4AF37;
    --ivory: #fffaf2;
    --text: #333;
}

body {
    color: var(--text);
    background: var(--ivory);
    line-height: 1.6;
}


/* Hero Section */

header {
    height: 100vh;

    background:
    linear-gradient(
        rgba(80,0,20,0.55),
        rgba(80,0,20,0.55)
    ),
    url("https://images.unsplash.com/photo-1519741497674-611481863552")
    center/cover;

    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;

    color:white;
}


header h1 {
    font-size:4rem;
    color:var(--champagne-gold);
    letter-spacing:2px;
}


header p {
    font-size:1.5rem;
    margin-top:15px;
}


.btn {

    display:inline-block;
    margin-top:25px;

    padding:14px 35px;

    background:var(--champagne-gold);

    color:var(--burgundy);

    text-decoration:none;

    font-weight:bold;

    border-radius:30px;

    transition:0.3s;

}


.btn:hover {

    background:white;

}



/* Sections */

section {

    padding:80px 10%;

    text-align:center;

}



h2 {

    font-size:2.6rem;

    margin-bottom:30px;

    color:var(--burgundy);

}



h2::after {

    content:"";

    display:block;

    width:80px;

    height:3px;

    background:var(--champagne-gold);

    margin:15px auto;

}




/* Cards */


.details {

display:flex;

justify-content:center;

gap:30px;

flex-wrap:wrap;

}



.card {

background:white;

padding:35px;

width:300px;

border-radius:15px;

border-top:5px solid var(--champagne-gold);

box-shadow:
0 10px 25px rgba(128,0,32,0.15);

}



.card h3 {

color:var(--burgundy);

margin-bottom:15px;

}




/* Timeline */


.timeline div {

background:white;

margin:20px auto;

padding:25px;

max-width:600px;

border-left:6px solid var(--champagne-gold);

border-radius:10px;

}



.timeline h3 {

color:var(--burgundy);

}




/* Gallery */


.gallery {

display:grid;

grid-template-columns:
repeat(auto-fit,minmax(220px,1fr));

gap:20px;

}



.gallery img {

width:100%;

height:280px;

object-fit:cover;

border-radius:15px;

border:5px solid var(--champagne-gold);

}




/* RSVP */


form {

max-width:500px;

margin:auto;

}



input,
textarea {

width:100%;

padding:15px;

margin:10px;

border:1px solid #d4af37;

border-radius:8px;

background:white;

}



button {

padding:14px 35px;

border:none;

background:var(--burgundy);

color:var(--champagne-gold);

font-weight:bold;

border-radius:30px;

cursor:pointer;

}



/* Footer */


footer {

background:var(--burgundy);

color:var(--champagne-gold);

padding:30px;

text-align:center;

font-size:1.2rem;

}

</style>
