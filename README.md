Download Link: https://assignmentchef.com/product/solved-sdev350-week4
<br>
In this lab, you will demonstrate you are comfortable creating users, profiles and roles.

<strong>You must connect to the provided AWS Oracle RDS environment and complete these task to earn credit for this lab. </strong>

<strong>Lab Requirements </strong>

<ol>

 <li>Create a unique Profile based on the following requirements:

  <ol>

   <li>Password complexity should meet requirements for Ora12 Verify function.</li>

   <li>User may have up to 3 concurrent sessions.</li>

   <li>User may have up to 4 consecutive failed attempts to log in before the account is locked.</li>

   <li>User may wait up till 120 days before their password must be changed.</li>

   <li>User account will be locked for 1 hours after the specified number of consecutive failed login attempts.</li>

   <li>Default values for other Profile parameters is acceptable</li>

   <li>You should name the Profile PFirstnameLastname where Lastname and Firstname are your First and Lastname</li>

  </ol></li>

 <li>Verify your Profile was successfully created by Creating and executing a SQL statement querying the appropriate Data Dictionary objects.</li>

 <li>Create 2 users assign them to the Permanent Tablespace of Users with a Quota of 30M. Assign the new users the Profile you established in Step 1 of this lab. Be sure to expire their passwords upon creation. Name the users as follows:

  <ol>

   <li>U1FirstnameLastname</li>

   <li>U2FirstnameLastname</li>

  </ol></li>

</ol>

Where Firstname and Lastname are your first and lastname.

<ol start="4">

 <li>Create a role allowing users assigned to be able to connect to the database and create tables. Name this R1FirstnameLastname where Firstname and Lastname are your first and lastname.</li>

 <li>Create two tables in your (root/admin) schema. Name them User1Data and User2Data. The tables should contain a primary key and 3 additional columns of your choice. Insert 3 records into each table.</li>

 <li>Provide privileges for U1FirstnameLastname and U2FirstnameLastname to be able to connect to the database and create tables. Be sure to use security best practices when assigning these privileges. In addition, provide one user the privileges to select from User1Data and Insert into User1Data. Provide the other user the privileges to select from User1Data and User2Data.</li>

 <li>Prepare and execute a detailed test plan to verify the two users have all the privileges they need but no additional privileges. Be sure to test by logging in as those users, changing their passwords, connecting, creating table and then using the assigned privileges in the User1Data and User2Data tables and performing and documenting other tests as required.</li>

</ol>


