<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="new.jsp">
        <Pre>Enter name :  <input type="text"  placeholder="name" ></input></Pre>
        <pre>Enter password: <input  type ="password" placeholder="password" ></input></pre>
        <pre>choose your class:</pre>
        <label for="101">
            <input type="radio" value="class IX" name="class" id="101">class IX
        </label>
        <label for="102">
            <input type="radio" value="class X" name="class" id="102">class X
        </label>
        <br>
        select your subjects:
        <br>
        <label for="11">
            <input type="checkbox"  value="option 1" name="option" id="11">option 1
        </label>
        <label for="12">
            <input type="checkbox" value="option 2" name="option" id="12">option 2
        </label>
        <label for="13">
            <input type="checkbox" value="option 3" name="option" id="13">option 3
        </label>
        <br>
        <br>
        select your city: 
        <select name="city" id="1001">
            <option value="delhi">delhi</option>
            <option value="mumbai">mumbai</option>
            <option value="bihar">bihar</option>
            <option value="goa">goa</option>
        </select>
        <br><br>
        <textarea name="feedback" placeholder=" enter feedback" rows="5" ></textarea>
        <br>
        <input type="submit" value="submit"></input>
    </form>
    
</body>
</html>
