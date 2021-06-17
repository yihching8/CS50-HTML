# CS50-HTML
<!DOCTYPE html>
<html>

<head>
	<link href="styles.css" rel="stylesheet" />
	<title>index</title>
	<script>
		function greet()
      { 
        alert('hello, '+ document.getElementById('name').value + '!');
      }
	</script>
</head>

<body>
	<table>
		<tr>
			<td><img src="chanel cute.jpg" width="720" height="380"/><h1>Hello, welcome to Niche!</h1></td>
      </tr>
    </table>
    <br>
    <form onsubmit="greet(); return false;">
      <input id="name"placeholder="name" type="name"/>
      <input type="submit"/>
    </form>
    </br>
      <h3>Place your reservation for the latest seasonal collections.</h3>
    
    <table>
      <tr>
        <td><img src="chanel AS2514.jpg" width="320" height="320"/><br><strong><center>AS2514 Gold-Tone Metal & Lambskin</center><strong></td>
        <td><img src="chanel A69900.jpg" width="320" height="320"/><br><strong><center>A69900 White Mini Iridescent Calfskin</center><strong></td>
      </tr>
      <tr>
        <td><img src="chanel A01112.jpg" width="320" height="320"/><br><strong><center>A01112 Black Tweed Diamantés & Silver</center><strong></td>
        <td><img src="chanel APink.jpg" width="320" height="320"/><br><strong><center>A01112 Pink Tweed & Gold Metal</center><strong></td>
      </tr>
    </table>
    </br>
   

     <br>
     <p>Please select the item you wish to reserve:</p>
     <input type="radio" name="reservation" value="Gold"> AS2514 Gold
     <input type="radio" name="reservation" value="White"> A69900 White Mini
     <p>
     <input type="radio" name="reservation" value="A01112"> A01112 Black
     <input type="radio" name="reservation" value="Pink"> A01112 Pink
     <p>
	    Get the <a href="https://CS50xCoursewebsite.yihching8.repl.co/rates.html" style="color:dodgerblue">exchange rates</a>.
    <br>  
     I agree to the <a href="https://CS50xCourseWebsite.yihching8.repl.co/terms.html" style="color:dodgerblue">terms & conditions:</a> <input name="agreement" type="checkbox"/>
     </p>
   </form>
  </body>
 

  <button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Reserved</button>

  <div id="id01" class="modal">
    <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
    <form class="modal-content" action="/action_page.php">
      <div class="container">
        <h1>Sign Up</h1>
        <p>Please fill in this form to create an account.</p>
        <hr>
        <label for="email"><b>Email</b></label>
        <input type="text" placeholder="Please enter your email" name="email" required>

        <label for="psw"><b>Password</b></label>
        <input type="password" placeholder="Please enter your password for new sign up or member sign in" name="psw" required>

        <label for="psw-repeat"><b>Repeat Password</b></label>
        <input type="password" placeholder="Please re-enter your password for new sign up only">
      
        <label>
         <input type="checkbox" checked="checked" name="remember" style="margin-bottom:15px"> Remember me
        </label>

        <p>By creating an account you agree to our <a href="https://CS50xCourseWebsite.yihching8.repl.co/terms.html" style="color:dodgerblue">Terms & Privacy</a>.</p>

        <div class="clearfix">
          <button type="submit" class="signupbtn">New Sign Up</button>
          <button type="submit" class="signinbtn">Member Sign In</button>
          <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
        </div>
      </div>
    </form>
</div>

<script>
// Get the modal
var modal = document.getElementById('id02');

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>
</body>
<p>
Setting up an account with Niche is faster than Starfish's singing!  Click on Starfish and tap any key, have fun!
</p>
  <iframe src="https://scratch.mit.edu/projects/520093850/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen=""></iframe>
</p>

</html>
