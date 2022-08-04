<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <META> element to your page <HEAD>.      -->
<!--  If necessary, please modify the charset parameter to specify the        -->
<!--  character set of your HTML page.                                        -->
<!--  ----------------------------------------------------------------------  -->

<META HTTP-EQUIV="Content-type" CONTENT="text/html; charset=UTF-8">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <FORM> element to your page.             -->
<!--  ----------------------------------------------------------------------  -->

<form action="https://webto.salesforce.com/servlet/servlet.WebToCase?encoding=UTF-8" method="POST">

<input type=hidden name="orgid" value="00D8Z000000s6fM">
<input type=hidden name="retURL" value="https://www.canva.com/design/DAFIE7WI2yU/tq64vJ8bjZRBBTPrPx0A-g/watch?utm_content=DAFIE7WI2yU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: These fields are optional debugging elements. Please uncomment    -->
<!--  these lines if you wish to test in debug mode.                          -->
<!--  <input type="hidden" name="debug" value=1>                              -->
<!--  <input type="hidden" name="debugEmail" value="aysegulerva@gmail.com">   -->
<!--  ----------------------------------------------------------------------  -->

<label for="name">Contact Name</label><input  id="name" maxlength="80" name="name" size="20" type="text" /><br>

<label for="email">Email</label><input  id="email" maxlength="80" name="email" size="20" type="text" /><br>

<label for="phone">Phone</label><input  id="phone" maxlength="40" name="phone" size="20" type="text" /><br>

<label for="subject">Subject</label><input  id="subject" maxlength="80" name="subject" size="20" type="text" /><br>

<label for="description">Description</label><textarea name="description"></textarea><br>

<label for="status">Status</label><select  id="status" name="status"><option value="">--None--</option><option value="New">New</option>
<option value="Working">Working</option>
<option value="Escalated">Escalated</option>
<option value="Closed">Closed</option>
</select><br>

<label for="reason">Case Reason</label><select  id="reason" name="reason"><option value="">--None--</option><option value="Installation">Installation</option>
<option value="Equipment Complexity">Equipment Complexity</option>
<option value="Performance">Performance</option>
<option value="Breakdown">Breakdown</option>
<option value="Equipment Design">Equipment Design</option>
<option value="Feedback">Feedback</option>
<option value="Other">Other</option>
</select><br>

<input type="submit" name="submit">

</form>
