# Docker-2
Create a dockerfile, docker-compose file which when executed must display your basic details in the website.

html Code

<!DOCTYPE html>
<html>
<head>
    <title>My Profile</title>
    <style>
        body {
            background: linear-gradient(120deg,#1d2671,#c33764);
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 80px;
        }
        .card {
            background: rgba(0,0,0,0.4);
            width: 400px;
            margin: auto;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 0 15px black;
        }
        h1 { color: #ffdd59; }
    </style>
</head>
<body>
<div class="card">
    <h1>Sethu Raman</h1>
    <h3>DevOps Engineer</h3>
    <p>Location : Chennai, India</p>
    <p>Skills : Linux | AWS | Docker | Git | Shell Scripting</p>
    <p>Learning : Kubernetes, CI/CD</p>
</div>
</body>
</html>
