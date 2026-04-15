# ramanujancollage
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
}

nav {
    display: flex;
    justify-content: space-between;
    padding: 20px 10%;
    background: #fff;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav a {
    text-decoration: none;
    color: #333;
    font-weight: 600;
}

header {
    height: 60vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: linear-gradient(135deg, #6e8efb, #a777e3);
    color: white;
    padding: 0 20px;
}

header h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.btn {
    margin-top: 20px;
    padding: 10px 25px;
    background: white;
    color: #6e8efb;
    text-decoration: none;
    border-radius: 25px;
    font-weight: bold;
    transition: 0.3s;
}

.btn:hover {
    background: #f0f0f0;
}

section {
    padding: 60px 10%;
    text-align: center;
}

footer {
    padding: 20px;
    background: #333;
    color: white;
    text-align: center;
}
