
<h2>Purple-eclipse</h2>
<p><strong>Target:</strong> `AB.0XY.00Z`</p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 80%; font-size: 12px;">
    <tr style="width: 70%;" valign="top">
        <td width="18%">
            <h3>Revisions</h3>
            <h4 style="list-style-type: none; padding-left: 0;">Site Map</h4>
            <a href="../homepage/homepage.md">Homepage</a>
            <br>
            <a href="../authenticate-user/account-signup.md">Authentication</a>
            <ul>
                <li><a href="account-signup.md">Sign up</a></li>
                <li><a href="account-login.md">Account Login</a></li>
                <li><a href="error-dialog.md">Error Dialog</a></li>
            </ul>
            <a href="../manage-comment/delete-comment.md">Forum Management</a>
            <ul>
                <li><a href="../manage-comment/delete-comment.md">Delete comment dialog</a></li>
                <li><a href="../manage-comment/edit-comment.md">Edit comment dialog</a></li>
                <li><a href="../manage-comment/post-comment.md">Post comment dialog</a></li>
            </ul>
            <a href="../manage-forum/add-forum.md">Discussion Creation/Participation</a>
            <ul>
                <li><a href="../manage-forum/add-forum.md">Add forum dialog</a></li>
                <li><a href="../manage-forum/add-subforum.md">Add subforum dialog</a></li>
                <li><a href="../manage-forum/delete-forum.md">Delete forum dialog</a></li>
                <li><a href="../manage-forum/delete-subforum.md">Delete subforum dialog</a></li>
                <li><a href="../manage-forum/edit-forum.md">Edit forum dialog</a></li>
                <li><a href="../manage-forum/edit-subforum.md">Edit subforum dialog</a></li>
            </ul>
            <a href="../manage-notification/receive-notification.md">Notification</a>
            <ul>
                <li><a href="../manage-notification/receive-notification.md">Receive notification dialog</a></li>
            </ul>
            <a href="../manage-thread/delete-thread.md">Multimedia Content Sharing</a>
            <ul>
                <li><a href="../manage-thread/delete-thread.md">Delete thread dialog</a></li>
                <li><a href="../manage-thread/edit-thread.md">Edit thread dialog</a></li>
                <li><a href="../manage-thread/manage-thread.md">Manage thread dialog</a></li>
                <li><a href="../manage-thread/view-thread.md">View thread dialog</a></li>
            </ul>
            <a href="">Search Functionality</a>
            <br><br>
            <a href="../manage-message/receive-message.md">Real-Time Messaging</a>
            <ul>
                <li><a href="../manage-message/receive-message.md">Receive message</a></li>
                <li><a href="docs/manage-message/send-message.md">Send message</a></li>
            </ul>
        </td>
        <td valign="top" style="width: 30%;">
           <p>User Not Logged In</p>
           <img src="/assets/home_not_logged.png" alt="Homepage">
           <p> User Logged In</p>
           <img src="/assets/home_logged.png" alt="Not logged in Hompage">
           <h2>Homepage</h2>
           <p>The Homepage serves as Visconn’s main entry point, providing users access to forums, subforums, and threads. It also contains the navigation menu, including the profile if the user is logged in, or the sign-in and sign-up buttons<br> if not. Additionally, it offers other functionalities such as search, notifications, messages, and management functionalities (for admin). The Login functionality allows users to securely authenticate into the system using their registered credentials (username or email address and password). This feature ensures only authorized users can access their accounts and perform actions within the platform.</p>
            <h2>Use Case Scenario</h2>
            <table border="1">
                <tr>
                    <td colspan="2" align="left">
                        Registration Verification Process
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>Actor(s) Admin, Registered User, Guest</td>
                </tr>
                <tr>
                    <th>Goal</th>
                    <td>
                        To access forums, subforums, threads, and use available features such as search, notifications, <br>and messages depending on the whether the user is authenticated or not.
                    </td>
                </tr>
                <tr>
                    <th>Precondtions</th>
                    <td>
                            1. The user must have access to the homepage URL. <br>
                            2. The user may or may not be logged into the platform.
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1.	The user navigates to the homepage.<br>
                        2.	If the user is authenticated:
                        <br> &nbsp&nbsp&nbsp&nbspThe homepage displays the profile of the user along with access to forums, subforums, <br>threads, search functionality, and notifications. If the user is admin, it displays access to <br>management related navigation.<br>
                        3.	If the user is authenticated:
                        <br>&nbsp&nbsp&nbsp&nbspThe homepage displays the profile of the user along with access to forums, subforums, <br>threads, search functionality, and notifications.<br>
                        4.	The user clicks on any forum, subforum, or thread to explore the content.<br>
                        5.	The user may interact with features like search, notifications, and messages depending on <br>the account status.
                    </td>
                </tr>
                <tr>
                    <th>Outcome: </th>
                    <td><strong> Success: The user successfully navigates to the desired content or interacts with the <br>features based on whether they are authenticated or not and their privileges.</td>
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
