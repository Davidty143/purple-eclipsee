
<h2>Purple-eclipse</h2>
<p><strong>Target:</strong> `AB.0XY.00Z`</p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 80%; font-size: 12px;">
    <tr style="width: 70%;">
        <td>
            <h3>Revisions</h3>
            <h4 style="list-style-type: none; padding-left: 0;">Site Map</h4>
            <a href="../homepage/homepage.md">Homepage</a>
            <br>
            <a href="../authenticate-user/account-signup.md">Authentication</a>
            <ul>
                <li><a href="../authenticate-user/account-signup.md">Sign up</a></li>
                <li><a href="../authenticate-user/account-login.md">Account Login</a></li>
                <li><a href="error-dialog.md">Error Dialog</a></li>
            </ul>
            <a href="delete-comment.md">Forum Management</a>
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
            <a href="delete-thread.md">Multimedia Content Sharing</a>
            <ul>
                <li><a href="delete-thread.md">Delete thread dialog</a></li>
                <li><a href="edit-thread.md">Edit thread dialog</a></li>
                <li><a href="manage-thread.md">Manage thread</a></li>
                <li><a href="view-thread.md">View thread dialog</a></li>
            </ul>
            <a href="">Search Functionality</a>
            <br><br>
            <a href="../manage-message/receive-message.md">Real-Time Messaging</a>
            <ul>
                <li><a href="../manage-message/receive-message.md">Receive message</a></li>
                <li><a href="../manage-message/send-message.md">Send message</a></li>
            </ul>
        </td>
        <td valign="top" style="width: 30%;">
            <a href="https://github.com/Davidty143/purple-eclipse/blob/main/docs/homepage/homepage.md">Homepage</a> &gt;
            <a href="https://github.com/Davidty143/purple-eclipse/tree/main/docs/manage-thread">Manage Thread</a>
            <br><br>
            <img src="https://github.com/user-attachments/assets/d557f3f8-536c-4ed7-8990-4fff6e8f81c6" alt="Manage Thread" width="200">
            <h2>Delete Thread</h2>
            <p>The "Delete Thread" feature allows users to permanently remove threads they have created. Admins can delete any thread, 
                with additional capabilities such as restoring or archiving deleted content. Only authorized users can delete threads, 
                and all deletions are logged for auditing purposes. Deleting a thread removes all associated replies and content.
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
                <td>Permanently delete a thread.
              </td>
              </tr>  
                <tr>
                    <th>Precondtions</th>
                    <td>
                        The user must be logged in to their account.<br>
                        The user must be the thread starter (poster) or the admin<br>
                        The thread to be deleted must exist.
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1. The user navigates to the thread they want to delete.
                        <br>
                        2.The user clicks the "Trash" icon next to the edit button.
                        <br>
                        3. The system prompts for confirmation to prevent accidental deletion.
                          <br>
                        4. The user or admin confirms the deletion.
                        <br>
                        5. The thread and all associated content (such as comment) is deleted.
                        <br>           
                    </td>
                </tr>
                <tr>
                    <th>Outcome: </th>
                    <td>The thread is permanently deleted from the system.
                </td>
                </tr>
            </table>   
          <tr>
              <td colspan="2" align="center">
                  © Tenza
              </td>
          </tr>
</table>
