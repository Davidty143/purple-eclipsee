<h2>Purple-eclipse</h2>
<p><strong>Target:</strong> `PE.020.002`</p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 80%; font-size: 12px;">
    <tr style="width: 70%;">
        <td valign="top">
            <h3 style="margin-top:0">Revisions</h3>
            <h4 style="list-style-type: none; padding-left: 0;">Site Map</h4>
            <p> Main page, Authentication, and Account Creation </p>
            <a href="../homepage">Main Page</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="../homepage/homepage.md"> Home Page </a></li>  
            </ul>
            <a href="/authenticate-user">Authentication</a>
            <ul>
                <li><a href="../authenticate-user/account-signup.md">Sign up</a></li>
                <li><a href="../authenticate-user/account-login.md">Account Login</a></li>
            </ul>
             <p> Forum Management </p>
            <a href="/manage-forum">Manage Forum</a>
            <ul>
                <li><a href=add-forum.md">Add forum</a></li>
                <li><a href="add-subforum.md">Add subforum</a></li>
                <li><a href="delete-forum.md">Delete forum</a></li>
                <li><a href="delete-subforum.md">Delete subforum</a></li>
                <li><a href="edit-forum.md">Edit forum</a></li>
                <li><a href="edit-subforum.md">Edit subforum</a></li>
                <li><a href="view-forum.md">View forum</a></li>
                <li><a href="view-subforum.md">View subforum</a></li>
            </ul>
            <a href="../manage-thread">Manage Thread</a>
            <ul>
                <li><a href="../manage-thread/delete-thread.md">Delete thread</a></li>
                <li><a href="../manage-thread/edit-thread.md">Edit thread</a></li>
                <li><a href="../manage-thread/manage-thread.md">Manage thread</a></li>
                <li><a href="../manage-thread/view-thread.md">View thread</a></li>
            </ul>
            <p> Forum and subforum browsing and joining, Multimedia Content Sharing</p>
            <a href="/manage-comment">Manage Comment</a>
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
            <a href="https://github.com/Davidty143/purple-eclipse/tree/main/docs/manage-forum/view-subforum.md">View Subforum</a>
            <br><br>
            <img src="../../assets/view_subforum(user).png" alt="View Subforum" width="1000">
            <h2>View Subforum</h2>
            <p>The "View Subforum" functionality enables users to access threads in a subforum, with pagination and filtering options for efficient browsing of the threads.</p>
            <h2>Use Case Scenario</h2>
            <table border="1">
                <tr>
                    <td colspan="2" align="left">
                      User Views Subforum
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>User, Admin, Guest</td>
                </tr>
                <tr>
                    <th>Goal</th>
                    <td>View the content of the  subforum page, including thread and its navigations.</td>
                </tr>  
                <tr>
                    <th>Preconditions</th>
                    <td>
                          The user must either be logged in or as a guest.<br>
                          The subforum must exist in the platform.<br>
                          The user must be on a subforum page.
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1. The system displays a list of threads associated with the subforum.<br>
                        2. The system provides pagination controls for users to navigate through pages of threads.<br>
                        3. The user can apply filters to narrow down the list of threads (e.g., by date, popularity, or specific tags).<br>
                        4. The user can interact with individual threads by clicking on them to view their content or post a comment.
                    </td>
                </tr>
                <tr>
                    <th>Outcome:</th>
                    <td>The user successfully views the subforum content, utilizes pagination and  filters for faster navigation.</td>
                </tr>
            </table>   
          <tr>
              <td colspan="2" align="center">
                  © Tenza
              </td>
          </tr>
</table>
