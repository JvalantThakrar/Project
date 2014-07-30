<?php include_once 'Default/header.php'
?>
	<div class="body">
		<div class="contact">
			<div>
				<div>
					<div class="contact">
						<h2>CONTACT FORM</h2>
						<div class="address">
							<span><span>A</span>ddress:</span>
							<p>B/125 Aalap Century,
							  University Road, RAJKOT - 360005							</p>
							<span><span>P</span>hone <span>N</span>umber:</span>
							<p>
								+91 982 409 0058							</p>
							<span><span>e-MAIL </span><span>id</span></span>
							<p>
								DEEPAKDEEVAN@GMAIL.COM</p>
					  </div>
						<h3><span>F</span>or <span>A</span>ny <span>I</span>nquiries, <span>P</span>lease <span>F</span>ill <span>o</span>ut <span>T</span>he <span>F</span>orm <span>B</span>elow.</h3>
						<form action="contacthelp.php" action="post">
							<table>
								<tr>
									<td><label for="name"><span>N</span>ame:</label></td>
									<td><input type="text" id="name" name="name"></td>
								</tr>
								<tr>
									<td><label for="email"><span>E</span>mail <span>A</span>ddress:</label></td>
									<td><input type="text" id="email" name="email"></td>
								</tr>
								<tr>
									<td><label for="subject"><span>S</span>ubject:</label></td>
									<td><input type="text" id="subject" name="subject"></td>
								</tr>
								<tr>
									<td><label for="message"><span>M</span>essage:</label></td>
									<td><textarea name="message" id="message" cols="30" rows="10"></textarea></td>
								</tr>
							</table>
							<input type="submit" value="Send" id="submit">
						</form>

					</div>
				</div>
			</div>
		</div>
	</div>
<?php include_once 'Default/footer.php'
?>
