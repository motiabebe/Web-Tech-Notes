# CSS Demo

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style type="text/css">
        .card{
            border: 1px cornflowerblue solid;
            padding: 5%;
            width: fit-content;
            height: max-content;
            background-color: rgb(4, 60, 130);
            border-radius: 10%;
            color: white;
        }
        .card-data {
            font-weight: bold;
        }
        .btn {
            padding: 6%;
            background-color: black;
            color: white;
            border-radius: 100px;
            border-style: none;
        }
        .btn:hover {
            background-color: white;
            color: black;
            transition: 300ms ease-in-out;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="card-title">
            <h4>John</h4>
        </div>
        <div class="card-data">
            <p>Hi, my name is John</p>
            <button class="btn">View Profile</button>
        </div>
    </div>
</body>
</html>
```