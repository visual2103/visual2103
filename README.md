<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text and Image Layout</title>
    <style>
        .container {
            display: flex;
            align-items: center; /* aliniază vertical imaginea și textul */
            justify-content: space-between; /* separă imaginea și textul */
            gap: 20px; /* spațiu între text și imagine */
        }
}
        .text {
            width: 50%; /* ajustează lățimea textului */
        }
{
        .image {
            width: 50%; /* ajustează lățimea imaginii */
            text-align: right;
        }
}
        img {
            max-width: 100%; /* face imaginea să fie responsive */
            height: auto;
        }
{
        ul {
            padding-left: 20px; /* margine pentru lista neordonată */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="text">
            <h1>Alina</h1>
            <p>My name is Alina, an innovative and driven Computer Engineering student pursuing a Bachelor's degree. Proficient in programming languages such as C/C++, Java, and Python. Proven ability to work effectively in a team and independently, with a strong attention to detail.</p>
            <p><strong>Languages and Tools:</strong></p>
            <ul>
                <li>DevOps, Microservices, Containers</li>
                <li>Cloud-native Projects</li>
                <li>Python, OpenCV</li>
            </ul>
        </div>
        <div class="image">
            <img src="URL_IMAGINE" alt="Image of developer working">
        </div>
    </div>
</body>
</html>
