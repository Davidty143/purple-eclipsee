<h2>Purple-eclipse</h2>
<p><strong>Target:</strong> `PE.010.006`</p>

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
            <h4> In-App Message </h4>
            <a href="../manage-message">Real-Time Messaging</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="../manage-message/send-message.md"> Send message </a></li>
                <li style="padding-left: 15px"> <a href="../manage-message/receive-message.md"> Receive message </a></li>
            </ul>
        </td>
        <td valign="top" style="width: 30%;">
            <a href="https://github.com/Davidty143/purple-eclipse/blob/main/docs/homepage/homepage.md">Homepage</a> &gt;
            <a href="https://github.com/Davidty143/purple-eclipse/tree/main/docs/authenticate-user">Authenticate User</a> &gt;
            <a href="https://github.com/Davidty143/purple-eclipse/tree/main/docs/authenticate-user">Account Login</a>
            <br><br>
            <img src="/assets/google_login.png" alt="Authenticate User">
            <h2>Authenticate User</h2>
            <p>The Login functionality allows users to securely authenticate into the system using their registered credentials (username or email address and password). This feature ensures only authorized users can access their accounts and perform actions within the platform.</p>
            <h2>Use Case Scenario</h2>
            <table border="1">
                <tr>
                    <td colspan="2" align="left">
                        User Login with Google
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>Registered User, System</td>
                </tr>
                <tr>
                    <th>Precondtions</th>
                    <td>
                            1. The user must have a registered account.
                            <br>
                            2. The user is not logged in.
                            <br>
                            3. The user must be on the login page.
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1.	The user clicks the “Login using google account button”.
                        <br>
                        2. The system redirects to google account authentication page.
                        <br>
                        3.	If the authentication is successful
                            <ul>
                                <li>The system grants the user access and redirects them to the homepage</li>
                                <li>The system creates a session for the user and stores a session token or <br> cookie for authentication.</li>
                            </ul>
                        4. If the authentication is unsuccessful
                            <ul>
                                <li>The system displays an error message</li>
                                <li>The system displays an error message</li>
                            </ul>
                    </td>
                </tr>
                <tr>
                    <th>Outcome: </th>
                    <td><strong>Success:</strong> The user can access protected content, such as their profile and <br> can perform actions on the platform</td>
                </tr>
            </table>
                <br>
             <img src="/assets/account_login.png" alt="Authenticate User">
            <p>The Login functionality allows users to securely authenticate into the system using their registered credentials (username or email address and password). This feature ensures only authorized users can access their accounts and perform actions within the platform.</p>
              <table border="1">
                <tr>
                    <td colspan="2" align="left">
                      User Login with Password
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>Registered User, System</td>
                </tr>
                  <tr>
                      <th>Goal</th>
                      <td>Authenticate the user and allow them access to the system with valid <br> credentials (username / email and password).</td>
                  </tr>
                <tr>
                    <th>Precondtions</th>
                    <td>
                            1. The user must be registered.
                            <br>
                            2. The user is not logged in.
                            <br>
                            3. The user must be on the login page.
                            <br>
                            4.	The user must have their login credentials.
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1. The user enters their email/username and password.
                        <br>
                        2. The user enters their email/username and password.
                        <br>
                        3. The system verifies if the email and password match a registered <br>user in the database.
                        <br>
                        4. If the credentials are valid
                            <ul>
                                <li>The system grants the user access and redirects them to the homepage.</li>
                                <li>The system creates a session for the user and stores a session<br> token or cookie for authentication.</li>
                            </ul>
                        5. If credentials are invalid
                            <ul>
                                <li>The system creates a session for the user and stores a session<br> token or cookie for authentication.</li>
                                <li>The user is allowed to try again.</li>
                            </ul>
                    </td>
                </tr>
                <tr>
                    <th>Outcome: </th>
                    <td>
                        <strong>Success:</strong> The user can access protected content, such as their profile and <br> can perform actions on the platform.
                        <br>
                        <br>
                        <strong>Failure:</strong> The system displays an error message, and the user is given  the <br> option to retry the login.
                    </td>
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
