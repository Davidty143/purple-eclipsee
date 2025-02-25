

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
            <a href="https://github.com/Davidty143/purple-eclipse/blob/main/docs/authenticate-user/account-login.md">Manage Comment</a>
            <br><br>
            <img src="https://github.com/user-attachments/assets/d557f3f8-536c-4ed7-8990-4fff6e8f81c6" alt="Manage Comment" width="200">
            <h2>Edit Comment</h2>
            <p>The "Edit Comment" feature allows users to modify their own comments inside a thread. Edits are logged, 
              and a timestamp is displayed to indicate changes. Only the comment poster can edit the comment.</p>
            <h2>Use Case Scenario</h2>
            <table border="1">
                <tr>
                    <td colspan="2" align="left">
                      User Comment on Thread
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>User, Admin</td>
                </tr>
              <tr>
                <th>Goal</th>
                <td>Allow users to edit their own comments and admins to edit any comment for moderation.</td>
              </tr>  
                <tr>
                    <th>Precondtions</th>
                    <td>
                          The user must be logged in to their account.<br>
                          The user must have previously posted the comment they wish to edit.
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1. The user navigates to the thread or post where they want to comment.
                        <br>
                        2. The user clicks the "Edit" option associated with their comment.
                        <br>
                        3. The comment's text becomes editable, and the user makes the desired changes.
                          <br>
                        4. The updated comment is saved and displayed with a timestamp reflecting the last edit.
                        <br>
                    </td>
                </tr>
                <tr>
                    <th>Outcome: </th>
                    <td>The comment is deleted and no longer visible in the thread.</td>
                </tr>
            </table>   
          <tr>
              <td colspan="2" align="center">
                  © Tenza
              </td>
          </tr>
</table>
