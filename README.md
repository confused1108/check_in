# check_in
<h4>The Application have 4 pages in total:</h4>
  
<b>Checkin: </b>Check in page (for users).
<br>
<b>Host_register: </b>For registration of host. Only a single host can register, there can't be multipe number of hosts.
<br>
<b>Host_login: </b> Login Page (for host).
<br>
<b>Users: </b>
<ul>
  <li>Contains table which shows all the checked-in users.</li>
  <li>Only host can access this page by logging into his account.</li>
  <li>Host can't access this page without login.</li>
  <li>Host can check out a user(checked in user) from this page.</li>
  <li>Host can also log out (from this page).</li>
  <li>When a user checks in,  a mail is sent to the registered host, entry of this user can be seen in the table of users page (only host can see it)</li>
  <li>When a user checks out, a mail us sent to the user itself and that user's entry is deleted from the table (on users page).</li>
  <br>
  <li><b>Index.js</b> is the file that contains all the routes of application.</li>
  <li>To send emails to the host and user (when a user checks-in and checks-out), you will have to enter your email address and password at some places in <b>index.js</b> (see attached pictures in repository) and turn on the access for less secure apps (when you are checking the functioning of application)</li>
  <li>You will have to use your Gmail account to check the functioning of application.</li>
</ul>
