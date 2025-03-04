
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
                <li><a href="/manage-thread.md">Manage thread dialog</a></li>
                <li><a href="/send-message.md">Send message</a></li>
            </ul>
        </td>
        <td valign="top" style="width: 30%;">
            <a href="https://github.com/Davidty143/purple-eclipse/blob/main/docs/homepage/homepage.md">Homepage</a> &gt;
            <a href="https://github.com/Davidty143/purple-eclipse/tree/main/docs/manage-forum">Send Message</a>
            <br><br>
            <img src="" alt="Send Message" width="200">
            <h2>Send Message</h2>
            <p>The "Send Message" feature allows users to send direct messages in the form of threads, enabling users to communicate <br>with others in an organized manner. A user can send multiple messages in a thread, or continue an existing conversation with a recipient.
            </p>
            <h2>Use Case Scenario</h2>
            <table border="1">
                <tr>
                    <td colspan="2" align="left">
                      User Create Forum
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>User, System</td>
                </tr>
              <tr>
                <th>Goal</th>
                <td>Allow users to send direct messages to other users.</td>
              </tr>  
                <tr>
                    <th>Precondtions</th>
                    <td>
                          The user is logged in to their account.<br>
                          The recipient must be a registered user on the platform.
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1. The user navigates to the messaging section, either from the main dashboard or by clicking the message<br> icon located in the header menu.<br>
                        2. The system displays the user's recent message threads along with a "Send a Direct Message" button.<br>
                        3. For a New Thread (New Recipient):<br>&nbsp&nbsp&nbsp
                            a. The user clicks on the "Send a Direct Message" button to start a new message thread.<br>&nbsp&nbsp&nbsp
                            b. A form appears containing the following fields:<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                                - Recipient: The user enters the username or email of the recipient.<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                                - Subject: The user enters the subject for the message (optional, depending on system settings).<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                                - Message: The user types the content of the message.<br>
                        4. For an Existing Thread (Continuing a Conversation):<br>&nbsp&nbsp&nbsp
                            a. If the user clicks on a previously sent message thread, the system loads that thread.<br>&nbsp&nbsp&nbsp
                            b. The message form now only contains the option to type and send a new message within that thread,<br>&nbsp&nbsp&nbsp
                            showing the history of the conversation (previous messages).<br>
                        5. The user clicks on the "Send" button.<br>
                        6. The system confirms that the message has been sent successfully.
                        <br>            
                    </td>
                </tr>
                <tr>
                    <th>Outcome: </th>
                    <td>
                      The message is sent successfully. If it’s a new thread, it appears as a new message thread in both the sender's and <br>recipient's inboxes. If it’s a continuation of an existing message thread, the message is added to the ongoing conversation.
                    </td>
                </tr>
            </table>   
          <tr>
              <td colspan="2" align="center">
                  © Tenza
              </td>
          </tr>
</table>


