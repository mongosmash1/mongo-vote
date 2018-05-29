**VIEWS**

*Home* (list of all polls by all users, site-wide stats)<br>
  / routes to /public/index.html
  
*Login* (github, facebook, or twitter)<br>
  /login routes to /public/login.html
  
*Dashboard* (account profile, list of my polls, overall poll stats)<br>
  /dashboard routes to /public/dashboard.html
  
*Edit Profile* (display name, email, and linked accounts)<br>
  /profile routes to /public/profile.html
  
*Create a poll* (title, choices, time limit)<br>
  /polls/new routes to /public/create-poll.html
  
*Delete a poll*<br>
  /polls/delete/:id routes to /public/poll-delete.html
  
*Vote on a poll* (prereq to see detail, can add custom vote, vote only once)<br>
  /polls/vote/:id routes to /public/poll-vote.html
  
*Detailed poll info* (results, graph, user comments, share, notify)<br>
  /polls/view/:id routes to /public/poll-detail.html