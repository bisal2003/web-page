<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>forms </title>
</head>

<body>
    <h1>forms</h1>
    <form action="Post">
        <div>
            <label for="Username">Enter your User name</label>
            <input Type="text" id="username" name="username" placeholder="Enter your User Name">
        </div>
        <div>
            Name:<input type="text" name="My name" placeholder="Your Name">
        </div>
        <br>
        Gender: Male<input type="radio" name="mygender"> Female<input type="radio" name="mygender"> Other<input
            type="radio" name="mygender">
        </br>
        <br>
        <label for="comment">Enter your comment</label>
        <br><textarea id="comment" rows="4" cols="50"></textarea>
        <br>
        Comment:
        <br><textarea name="comment" rows="4" cols="50" placeholder="enter your comment"></textarea>
        <br>
        <select name="fruits">
            <option value="apple">Apple</option>
            <option value="mango">Mango</option>
            <option value="guava">guava</option>
        </select>
        </br>

        <input type="submit" value="submit now">
        <input type="reset" value="reset now">
        </br>
    </form>
</body>

</html>
