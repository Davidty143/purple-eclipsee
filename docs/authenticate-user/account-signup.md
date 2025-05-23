<h2>Purple-eclipse</h2>
<p><strong>Target:</strong> `PE.020.002`</p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 80%; font-size: 12px;">
    <tr style="width: 70%;">
        <td valign="top">
            <h3 style="margin-top:0">Revisions</h3>
            <h4 style="list-style-type: none; padding-left: 0;">Site Map</h4>
            <p> Main page, Authentication, and Account Creation </p>
            <a href="/homepage">Main Page</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="../homepage/homepage.md"> Home Page </a></li>  
            </ul>
            <a href="/authenticate-user">Authentication</a>
            <ul>
                <li><a href="account-signup.md">Sign up</a></li>
                <li><a href="account-login.md">Account Login</a></li>
            </ul>
             <p> Forum Management </p>
            <a href="../manage-forum">Manage Forum</a>
            <ul>
                <li><a href="../manage-forum/add-forum.md">Add forum</a></li>
                <li><a href="../manage-forum/add-subforum.md">Add subforum</a></li>
                <li><a href="../manage-forum/delete-forum.md">Delete forum</a></li>
                <li><a href="../manage-forum/delete-subforum.md">Delete subforum</a></li>
                <li><a href="../manage-forum/edit-forum.md">Edit forum</a></li>
                <li><a href="../manage-forum/edit-subforum.md">Edit subforum</a></li>
            </ul>
            <a href="../manage-thread">Manage Thread</a>
            <ul>
                <li><a href="../manage-thread/delete-thread.md">Delete thread</a></li>
                <li><a href="../manage-thread/edit-thread.md">Edit thread</a></li>
                <li><a href="../manage-thread/manage-thread.md">Manage thread</a></li>
                <li><a href="../manage-thread/view-thread.md">View thread</a></li>
            </ul>
            <p> Forum and subforum browsing and joining, Multimedia Content Sharing</p>
            <a href="../manage-comment">Manage Comment</a>
            <ul>
                <li><a href="../manage-comment/delete-comment.md">Delete comment</a></li>
                <li><a href="../manage-comment/edit-comment.md">Edit comment</a></li>
                <li><a href="../manage-comment/post-comment.md">Post comment</a></li>
            </ul>
            <p> Notification System </p>
            <a href="../manage-notification">Notification</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="../manage-notification/recieve-notification.md">Recieve notification </a></li>
                <li style="padding-left: 15px"> <a href="../manage-notification/delete-notification.md"> Delete comment </a></li>    
            </ul>
            <p> Search Feature </p> 
            <a href="../search-functionality">Search Functionality</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="../search-functionality/search-thread.md"> Search Thread </a></li>
                <li style="padding-left: 15px"> <a href="../search-functionality/search-user.md"> Search User </a></li>
            </ul>
            <p> Manage Profile</p>
            <a href="../manage-profile">Profile</a>
            <ul>
                <li><a href="../manage-profile/edit-profile.md">Edit Profile</a></li>
                <li><a href="../manage-profile/view-profile.md">View Profile</a></li>
            </ul>
            <h4> In-App Message </h4>
            <a href="../manage-message">Real-Time Messaging</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="../manage-message/send-message.md"> Send message </a></li>
                <li style="padding-left: 15px"> <a href="../manage-message/receive-message.md"> Receive message </a></li>
            </ul>
            <p> Manage User </p>
            <a href="../manage-user">Manage User</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="../manage-user/ban-user.md"> Ban User </a></li>
                <li style="padding-left: 15px"> <a href="../manage-user/restrict-user.md"> Restrict User </a></li>
            </ul>
        </td>
        <td valign="top" style="width: 30%;">
            <a href="https://github.com/Davidty143/purple-eclipse/blob/main/docs/homepage/homepage.md">Homepage</a> &gt;
            <a href="https://github.com/Davidty143/purple-eclipse/blob/main/docs/authenticate-user">Account Sign-up</a>
            <br><br>
            <img src="/assets/account_signup.png" alt="User Signup">
            <h2>Account Sign-up</h2>
            <p>The Login functionality allows users to securely authenticate into the system using their registered 
                credentials (username or email address and password). This feature ensures only authorized users can
                access their accounts and perform actions within the platform.</p>
            <h2>Use Case Scenario</h2>
            <table border="1">
                <tr>
                    <td colspan="2" align="left">
                        User Sign-Up for New Account
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>New User, System</td>
                </tr>
                 <tr>
                      <th>Goal</th>
                      <td>Register an account by providing necessary information and receiving a verification email.</td>
                  </tr>    
                <tr>
                    <th>Precondtions</th>
                    <td>
                            1. The user is not logged in.
                            <br>
                            2. The user must be on the Sign-Up page.
                            <br>
                            3. The user must have an email address and a username that is not already registered.
                    </td>
                </tr>    
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1. User navigates to the sign-up dialog and enters their <br>username, email, password, and confirms the password.
                        <br>
                        2. The system checks if the username is already registered.
                        <ul>
                            <li>If yes, show the error “username already exist”</li>
                            <li>If no, proceed to next step</li>
                        3.	If the authentication is successful
                            <ul>
                                <li>The system grants the user access and redirects them to the homepage</li>
                                <li>The system creates a session for the user and stores a session token or <br> cookie for authentication.</li>
                            </ul>
                        4. The system checks if the email is already registered
                            <ul>
                                <li>If yes, show the error “Email already registered”</li>
                                <li>If no, proceed to email verification</li>
                            </ul>
                        5. The system verifies the password and confirm password match.
                            <ul>
                                <li>If they don’t match, show an error message "Passwords do not match."</li>
                                <li>If they match, proceed.</li>
                            </ul>
                        6. The Signup button must now be clickable.
                    </td>
                </tr>
                <tr>
                    <th>Outcome: </th>
                    <td><strong>Success:</strong> The user must be able to click the register  button and redirect to registration <br>verification dialog. </td>
                </tr>
            </table>
            <img src="/assets/email_verification.png" alt="Authenticate User">
            <h2>Email Verification</h2>
            <p>The Email Verification functionality ensures that a user’s email address is valid and accessible before granting full access to the system. 
                The system sends an email with a verification link or code to the user's provided email address, and the user is required to confirm their email 
                by clicking the link or entering the code.</p>
            <h2>Use Case Scenario</h2>
            <table border="1">
                <tr>
                    <td colspan="2" align="left">
                      Registration Verification Process
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>New User, System</td>
                </tr>
                 <tr>
                      <th>Goal</th>
                      <td>Verify the user's email address after they have signed up, ensuring that the email is valid<br> and that the user has access to it.</td>
                  </tr>    
                <tr>
                    <th>Precondtions</th>
                    <td>
                            1. The user has completed the registration form.
                            <br>
                            2. The system has sent a verification email to the user's provided email address.
                            <br>
                            3. The user has access to their email inbox.
                            <br>
                            4. The user has not yet verified their email.
                    </td>
                </tr>    
                <tr>
                    <th>Main Scenario</th>
                <td>
                    1. The user has not yet verified their email.
                    <br>
                    2. User accesses the verification email.
                    <br>
                    3. User accesses the verification email
                       <br>
                    4. System verifies the email.
                    <br>
                    5. User is redirected to the confirmation page
                    <br>
                    6. User is redirected to the home page.
                </td>
            </tr>
                <tr>
                    <th>Outcome: </th>
                    <td>The user's email address is verified, and their account is full registered. <br>The user is able to log in on Visconn.</td>
                </tr>
            </table>
        </td>
    </tr>
    <tr>
        <td colspan="2" align="center">
            © Tenza
        </td>
    </tr>
</table>
