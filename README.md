<html>
    <head>
        <title>
            Starting from forms, inputs
        </title>
    </head>

    <body>
        <p>
            Write something inside this box <input type="text" id="s">
            <label for="s">search</label>
        </p>

        <h3>
            Given below is a form consist of textbox,radio,checkbox.
        </h3>

        <form>
            <label for="tb1">Textbox:</label><input type="text" id="tb1"><br><br>
            
            <input type="radio" id="r1">
            <label for="r1">Radio</label><br><br>

            <input type="checkbox" id="cb1">
            <label for="cb1">Checkbox</label><br>
        </form>
        
        <br>

        <h3>Another form input with a submit button</h3>
        <form>
            <label for="tb2">Enter you email</label>
            <br>
            <input type="email" id="tb2" name="email" value="abc@gmail.com">
            
            <br><br>
            
            <label for="passwd">Enter your password</label>
            <br>
            <input type="password" id="passwd" name="password">
            
            <br><br>

            <label for="ph.number">Enter your Mobile number</label>
            <br>
            <input type="tel" id="ph.number" name="Mobile_number">
            
            <br><br>
            
            <label for="tb3">Enter you city</label>
            <br>
            <input type="text" id="tb3" name="city">
            
            <br><br>

            <label>Choose the payment method:</label>
            <input type="radio" id="r2" name="pay" value="cash">
            <label for="r2">Cash</label>
            <input type="radio" id="r3" name="pay" value="card">
            <label for="r3">Card</label>

            <br><br>

            <label for="fav_colour">Select your favorite colour:</label>
            <select name="Fav colour" id="fav_colour">
                <option value="r">RED</option>
                <option value="g">GREEN</option>
                <option value="b" selected>BLUE</option>
            </select>

            <br><br>
            

            <input type="submit">
        </form>

    </body>
</html>
