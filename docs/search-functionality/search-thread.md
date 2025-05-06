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
            <p> Notification Feature </p>
            <a href="../manage-notification">Notification</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="../manage-notification/recieve-notification.md">Recieve notification </a></li>
                <li style="padding-left: 15px"> <a href="../manage-notification/delete-notification.md"> Delete notification </a></li>    
            </ul>
            <p> Search Feature </p> 
            <a href="../search-functionality">Search Functionality</a>
            <ul style="list-style-type: none ; padding-left: 0">
                <li style="padding-left: 15px"> <a href="search-thread.md"> Search Thread </a></li>
                <li style="padding-left: 15px"> <a href="search-user.md"> Search User </a></li>
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
            <a href="https://github.com/Davidty143/purple-eclipse/tree/main/docs/authenticate-user">Search thread</a>
            <br><br>
             <img src="/assets/account_login.png" alt="Authenticate User">
            <h2> Search Threads </h2>
            <p>The “Search Threads” feature enables users to easily find threads available on the platform. It includes search filters to help refine results and enhance user convenience.</p>
            <h2>Use Case Scenario</h2>
              <table border="1">
                <tr>
                    <td colspan="2" align="left">
                      Search Threads
                    </td>
                </tr>
                <tr>
                    <th>Actor(s)</th>
                    <td>Registered User, System</td>
                </tr>
                  <tr>
                      <th>Goal</th>
                      <td>Enable users to search and locate threads available on the platform.</td>
                  </tr>
                <tr>
                    <th>Preconditions</th>
                    <td>
                            1. The user must be registered.
                            <br>
                            2. The user must be logged in to their account.
                            <br>
                    </td>
                </tr>
                <tr>
                    <th>Main Scenario</th>
                    <td>
                        1. The user logs in using valid credentials.
                        <br>
                        2. The system redirects the user to the home page, which includes a search bar and displays available threads.
                        <br>
                        3. The user selects filter options (e.g., by username or thread title) to refine the search.
                        <br>
                        4. The user enters a keyword, either the username of a thread author or the thread title, into the search bar.
                        <br>
                        5. The system searches the database based on the user’s input and selected filters.
                        <br>
                        6. The system displays a list of matching threads.
                        <br>
                        7. The user selects a thread from the results and can interact with it (e.g., read, comment, or like)
                    </td>
                </tr>
                <tr>
                    <th>Outcome: </th>
                    <td
                       <br>The user successfully locates and interacts with the desired thread.</br>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
