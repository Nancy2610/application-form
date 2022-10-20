<body>
    <form action="">
<center>
    <h1>Application Form</h1>
</center>
<h2>Applicant Details</h2>
<p>required fields are followed by a *</p>
<p>Name : * <input type="text" required></p>
<fieldset>
    <legend>Gender</legend>
<p>
<h3> Male <input type="radio" name="gender" id="male" required> Female <input type="radio" name="gender" id="female" required> Other <input type="radio" name="gender" id="other" required></h3> 
</p>
</fieldset>
<p> Father's Name :*<textarea name="fname" id="fname" cols="40" rows="2"></textarea>  </p>
<p> Mother's Name :*<textarea name="mname" id="mname" cols="40" rows="2"></textarea>  </p>
<p>
    Category :* <select name="category" id="category" required>
        <option value="">--Select a Category--</option>
        <option value="visa">General</option>
        <option value="mastercard">SC/ST</option>
        <option value="rupay">OBC</option>
        <option value="rupay">Pwd</option>
    </select>
</p>
<p> Address : <textarea name="address" id="address" cols="100" rows="5" ></textarea></p>
<p>Email :*<input type="email" name="email" id="email" required></p>
<p>Pincode :* <input type="number" name="pincode" id="pincode"required></p>
<center><h1>Payment Gateway</h1></center>

<h2>Payment Details</h2>
<p>
    Card Holder's Name :* <input type="name" name="holder_name" id="holder_name" required>
</p>
<p>
    Card Type :* <select name="cardtype" id="cardtype" required>
        <option value="">--Select a Card Type--</option>
        <option value="visa">Visa</option>
        <option value="mastercard">Master Card</option>
        <option value="rupay">Rupay</option>
    </select>
</p>
<p>
    Card Number :* <input type="number" name="card_number" id="card_number" required>
</p>
<p>
    Expiration Date :* <input type="date" name="expiration_date" id="expiration_date" required>
</p>
<p>
    CVV :* <input type="password" name="cvv" id="cvv" required>
</p>
<p>
    <input type="submit" value="Pay Now">
</p>
    </form>
    
</body>
