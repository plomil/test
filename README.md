<button>Ouvre toi</button>
button {
font-size: 24px;
color: #020e26
background-color: transparent;
border: 1px solid #020e26;
border-radius: 48px;
padding: 12px 32px;
transition: 0.4s;
}

button:hover {
color: #ffffff;
}

button: :before {
content: "";
position: absolute;
height: 62px;
width: 300px;
z-index: -1;
border-radius: 48px; 
background-color: #3bd9d9;
transform: translate(-24px, -8px);
transition: 0.4s;
}

button:*hover*: :before {
background-color: #b527cf;
transform: translate(-33px, -13px);
}

