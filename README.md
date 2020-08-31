<html>
  <h1>Should Carter get a Kiss on the Full Moon?</h1>
  <h>We surveyed 300 participants and here are the results!</h>
  <table>
    <tr>
      <td>Yes</td>
      <td>147</td>
     <tr>
       <td>Yes, but in grey</td>
       <td>153</td>
  </table>

<?php
if ($_POST['submit'])
 {
 $value=$_POST['result'];
 echo "You chose $value";
 }
?>

<form action="poll.php" method="post">
What do you say?<br />
<input type="radio" name="result" value="Yes" /> Ford<br />
<input type="radio" name="result" value="No" /> Chevy<br />

      
