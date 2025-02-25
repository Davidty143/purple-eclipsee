<h2>Purple-eclipse</h2>
<p><strong>Target:</strong> `AB.0XY.00Z`</p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 80%; font-size: 12px;">
    <tr style="width: 70%;">
        <td>
            <h3>Revisions</h3>
            <h4 style="list-style-type: none; padding-left: 0;">Site Map</h4>
            <a href="">Homepage</a>
            <br>
            <a href="">Authentication</a>
            <ul>
                <li><a href="docs/authenticate-user/account-signup.md">Sign up</a></li>
                <li><a href="docs/authenticate-user/account-login.md">Account Login</a></li>
                <li><a href="docs/authenticate-user/error-dialog.md">Error Dialog</a></li>
            </ul>
            <a href="">Forum Management</a>
            <ul>
                <li><a href="docs/manage-comment/delete-comment.md">Delete comment dialog</a></li>
                <li><a href="docs/manage-comment/edit-comment.md">Edit comment dialog</a></li>
                <li><a href="docs/manage-comment/post-comment.md">Post comment dialog</a></li>
            </ul>
            <a href="">Discussion Creation/Participation</a>
            <ul>
                <li><a href="docs/manage-forum/add-forum.md">Add forum dialog</a></li>
                <li><a href="docs/manage-forum/add-subforum.md">Add subforum dialog</a></li>
                <li><a href="docs/manage-forum/delete-forum.md">Delete forum dialog</a></li>
                <li><a href="docs/manage-forum/delete-subforum.md">Delete subforum dialog</a></li>
                <li><a href="docs/manage-forum/edit-forum.md">Edit forum dialog</a></li>
                <li><a href="docs/manage-forum/edit-subforum.md">Edit subforum dialog</a></li>
            </ul>
            <a href="">Notification</a>
            <ul>
                <li><a href="docs/manage-notification/receive-notification.md">Receive notification dialog</a></li>
                <li><a href="docs/manage-notification/delete-notification.md">Delete notification dialog</a></li>
            </ul>
            <a href="">Multimedia Content Sharing</a>
            <ul>
                <li><a href="docs/manage-thread/delete-thread.md">Delete thread dialog</a></li>
                <li><a href="docs/manage-thread/edit-thread.md">Edit thread dialog</a></li>
                <li><a href="docs/manage-thread/manage-thread.md">Manage thread dialog</a></li>
                <li><a href="docs/manage-thread/view-thread.md">View thread dialog</a></li>
            </ul>
            <a href="">Search Functionality</a>
            <br><br>
            <a href="">Real-Time Messaging</a>
            <ul>
                <li><a href="docs/manage-message/edit-message.md">Edit message dialog</a></li>
                <li><a href="docs/manage-message/send-message.md">Send message</a></li>
                <li><a href="docs/manage-message/delete-message.md">Delete message dialog</a></li>
            </ul>
        </td>
        <td valign="top" style="width: 30%;">
            <a href="https://github.com/VSUrhuel/voyager/blob/main/docs/homepage/homepage.md">Homepage</a> &gt;
            <a href="https://github.com/Davidty143/purple-eclipse/blob/main/docs/authenticate-user/account-login.md">Authenticate User</a>
            <br><br>
            <img src="https://github.com/user-attachments/assets/d557f3f8-536c-4ed7-8990-4fff6e8f81c6" alt="Authenticate User" width="200">
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
              <table border="1">
                <tr>
                    <td colspan="2" align="left">
                      User Login Using with Password
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
