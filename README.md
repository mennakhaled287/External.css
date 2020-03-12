# External.css
<!DOCTYPE html>
<html lang="en" dir="ltr">
<html >
  <head>

    <meta charset="utf-8">
    <title></title>
    </head>
    <body>
    <h1> Online Shopping</h1>

    <title>Question Form</title>
    <link rel="stylesheet" href="styles/External;stylesheet.css">
    <style>


      input:invalid{
        border:2px dashed red ;
      }

      input:valid{
        border:2px solid black;s
      }
      textarea:invalid{
        border:2px dashed red ;
      }
      textarea:valid {
        border:2 px solid black;
      }
</style>
</head>
  <body>
<form>
  <p> How can I help you?</p>
  <form>  <fieldset>
    <label >Name : </label>
    <input type="text"  maxlength="4" minlength="3" required><br/><br/>
    <select id="simple" name="simple"required>
      <option selected >Topic</option>
      <option selected >My Account</option>
      <option selected >Data privacy</option>
      <option selected >payment</option>
      <option selected >shipping and delivery</option>
      <option >Return </option>
    </select><br/><br/>
    <label .Question:</label>

    <textarea cols ="40" rows ="4" required></textarea><br/><br/>
    <label >Email:</label>
    <input type="email" id="email" name ="email" multiple required><br/><br/>
    <label >phone number :+60</label>
    <input type ="number" maxlength="6" required><br/><br/>
     <button type="submit" >submit</button>
     <button type ="Reset">Reset</button>
   </fieldset ></form>
 </body>
</html>
<style>
*{font-family: Arial;}
body {
  color : blue;
  background-color: #E6E6FA;
  border: 1px solid black;

}
h1 {
color :#191970;
font-family: Times New Roman ;

}
h2 {
  border: 3px dashed blue;

}
.classforcontact{
  color: #291970;
  border: 3px dashed blue ;
}
#IDselector{
  background-color: #591970;

}


</style>

</html>
