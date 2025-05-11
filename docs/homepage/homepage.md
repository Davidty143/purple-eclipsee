<h2>Purple-eclipse</h2>
<p><strong>Target:</strong> `PE.020.001`</p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 80%; font-size: 12px;">
    <tr style="width: 70%;">
        <td valign="top">
            <h3 style="margin-top:0">Revisions</h3>
            <h4 style="list-style-type: none; padding-left: 0;">Site Map</h4>
            <p> Main page, Authentication, and Account Creation </p>
            <a href="/homepage">Main Page</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="/homepage.md"> Home Page </a></li>  
            </ul>
            <a href="/authenticate-user">Authentication</a>
            <ul>
                <li><a href="../authenticate-user/account-signup.md">Sign up</a></li>
                <li><a href="../authenticate-user/account-login.md">Account Login</a></li>
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
                    <td>Admin, Registered User, Guest</td>
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
