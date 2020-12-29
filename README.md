# Form
form using html
<html>
<head>
    <title></title>
    <meta charset="iso-8859-4">
    <style type="text/css">
    .style2
    {
    width: 35%;
    background-color:aliceblue;
    text-align: center;
    margin-left: 31%;
        }
        h1 {margin-left:45%;}
    </style>
    <style>
        h1 { color: firebrick}
        h1{ font-size: 45px}
        h1{ font-family: monospace}
    </style> 
    </head>
    <body>
    <form action="" method="post">
        <caption><h1>Sign Up</h1></caption>
        <input type="image" src="free.jpg" alt="logo image" class="style2"/>
        <table class="style2">
            <tr>
            <td>
                Name :</td>
            <td><input type="text" id="text1" autofocus="autofocus" pattern="[A-Za-z]{3}" placeholder="Enter your name" required="required"/></td>
                   </tr>
            <tr>
            <td>
                E-mail :</td>
            <td>
                <input type="email" required="required"/>
                        </td></tr>
            <tr>
            <td>
                 Password :</td>
            <td><input type="password" id="password1" required/> </td></tr>
            <tr>
            <td>
                Re-enter password :</td>
            <td>
                <input type="password" id="password2" required/></td></tr>
            <tr>
            <td>Phone number :</td>
            <td><input type="number" pattern="(^[0-9]{1,10})"/></td></tr>
            <tr>
            <td>
                Date of Birth :</td>
            <td><input type="date" id="date1"/></td></tr>
            <tr><td>
                Select Qualification :
                </td><td>
                <input list="Education">
                <datalist id="Education">
                <option value="B.E">
                <option value="B.Com">
                <option value="B.A">
                <option value="MBA">
                <option value="B.Sc">
                <option value="MCA">
                    </datalist>
                </td> </tr>
            <tr><td>
                Course Date :</td>
            <td>
                <input type="date" id="date2"/>
                </td></tr>
            <tr><td>
                Submit</td>
                <td>
                <input type="submit" id="submit1"/>
                </td></tr>
        </table>
        </form>
        </body>
</html>
