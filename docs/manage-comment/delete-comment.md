
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
            <a href="https://github.com/Davidty143/purple-eclipse/blob/main/docs/homepage/homepage.md">Homepage</a> &gt;
            <a href="https://github.com/Davidty143/purple-eclipse/tree/main/docs/manage-comment">Manage Comment</a>
            <br><br>
            <img src="" alt="Manage Comment" width="200">
            <h2>Delete Comment</h2>
            <p>The "Delete Comment" feature allows authorized users, such as the comment poster or admins,
              to permanently remove comments from a thread. Admins have the ability to delete any comment for moderation,
              while users can only delete their own. </p>
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
                <td>Permanently remove a comment from a thread.</td>
              </tr>  
                <tr>
                    <th>Precondtions</th>
                    <td>
                          The user must be logged in to their account.<br>
                          The user must have previously posted the comment they wish to edit.<br>
                          The admin can delete any comment for moderation.
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1. The user navigates to the comment they want to delete.
                        <br>
                        2. The user clicks the "Trash" icon next to the "Edit" icon associated with their comment.
                        <br>
                        3. If the user is an admin, they can delete any comment in the thread.
                          <br>
                        4. A confirmation prompt appears to prevent accidental deletion.
                        <br>
                        5. The user confirms the deletion.
                        <br>
                        6.	The comment is permanently removed from the thread.
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
