

<h2>Purple-eclipse</h2>
<p><strong>Target:</strong> `AB.0XY.00Z`</p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 80%; font-size: 12px;">
    <tr style="width: 70%;">
        <td>
            <h3>Revisions</h3>
            <h4 style="list-style-type: none; padding-left: 0;">Site Map</h4>
            <a href="">Homepage</a>
            <br>
            <a href="">Mange Comment</a>
            <ul>
                <li><a href="docs/authenticate-user/account-signup.md">Sign up</a></li>
                <li><a href="docs/authenticate-user/account-login.md">Account Login</a></li>
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
            <a href="https://github.com/Davidty143/purple-eclipse/blob/main/docs/homepage/homepage.md">Homepage</a> &gt;
            <a href="https://github.com/Davidty143/purple-eclipse/tree/main/docs/manage-thread">Restrict User</a>
            <br><br>
            <img src="/assets/view_thread(user).png" alt="Restrict User">
            <h2>Restrict User</h2>
            <p>The "View Thread" feature allows users to view a thread's content, including the title, content, and comments, with access controlled by user permissions.
              Logged-in users can interact with the thread, while guests can only read it.
           </p>
            <h2>Use Case Scenario</h2>
            <table border="1">
                <tr>
                    <td colspan="2" align="left">
                     User Posts Thread
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>User, Admin, Guest</td>
                </tr>
              <tr>
                <th>Goal</th>
                <td>View the details of a specific thread, including the topic, content, and comments.
              </td>
              </tr>  
                <tr>
                    <th>Precondtions</th>
                    <td>
                          1. The thread must exist.<br>
                          2. The user must have access to the thread.<br>
                          3. If the user is a guest, the thread must be publicly accessible.
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1. The user navigates to the home page or the desired forum or subforum.
                        <br>
                        2. The user selects a thread to view.
                        <br>
                        3. The system displays the thread’s title, content, and a list of all comments.
                          <br>
                        4. The user enters a valid title, tags, and content for the thread.
                        <br>
                        5. If the user is logged in, they can also see additional options such as commenting.
                        <br>            
                        6. The user may scroll through the comments, view replies, or interact with the content.
                    </td>
                </tr>
                <tr>
                    <th>Outcome: </th>
                    <td>The user is able to view the thread and all associated content.
                </td>
                </tr>
            </table>   
          <tr>
              <td colspan="2" align="center">
                  © Tenza
              </td>
          </tr>
</table>
