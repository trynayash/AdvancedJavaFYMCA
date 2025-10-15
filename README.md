# AdvancedJavaFYMCA


<!DOCTYPE html>
<html>
    <head> 
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        <title>JSP Page</title>
    </head>
    <body>
        <form action="process.jsp" method="POST">
            <table border="1" cellpadding="20px" align="center">
                <thead>
                    <tr>
                        <th colspan="2">Registration Form</th>
                    </tr>
                </thead>
                <tr>
                    <td><label>Full Name</label></td>
                    <td><input id="text" type="text" value="" placeholder="type here..."></td>
                </tr>
                <tr>
                    <td><label>Email</label></td>
                    <td><input id="email" type="email" value="" placeholder="type here..."></td>
                </tr>
                <tr>
                    <td><label>Date of Birth</label></td>
                    <td><input id="dob" type="text" value=""></td>
                </tr>
                <tr>
                    <td><label>Educational Qualification</label></td>
                    <td><select>
                            <option disabled=""> ---Qualification--- </option>
                            <option value="SSC">SSC</option>  
                            <option value="HSC">HSC</option>
                            <option value="Diploma">Diploma</option>
                            <option value="Graduation">Graduation</option>
                            <option value="Post-Graduation">Post-Graduation</option> 
                        </select></td>
                </tr>
                <tr>
                    <td><label>Write about yourself</label></td><br></br>
                    <td><textarea id="waf" value="" placeholder="type here..."></textarea></td>
                </tr>
                <tr>
                   <td>Gender</td>
                   <td>
                        <input type="radio" name="gen" value="male"/> Male
                        <input type="radio" name="gen" value="female"/> Female
                   </td>
                </tr>
                    <td colspan="2" align="center">
                        <input type="submit" value="Submit Button">
                        <input type="reset" value="Reset">
                    </td>
                </tr>
            </table>
        </form>
    </body>
</html>

