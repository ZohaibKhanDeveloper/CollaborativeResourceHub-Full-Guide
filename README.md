<div align="center">
  <h1>🚀 CollabHub: Full-Stack Resource Orchestration</h1>
  <p><strong>A Scalable Knowledge-Sharing Ecosystem built with Django REST Framework, React, and PostgreSQL.</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
    <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" />
  </p>
</div>

<hr />
<h2>Backend Repository: <a href="https://github.com/ZohaibKhanDeveloper/CollaborativeResourceHub-Backend" target='_blank'>Check Here</a></h2>
<h2>Frontend Repository: <a href="https://github.com/ZohaibKhanDeveloper/CollaborativeResourceHub-Frontend" target='_blank'>Check Here</a></h2>
<h2>📖 Project Overview</h2>
<p>
  CollabHub is a 12-page professional platform designed for structured knowledge sharing. Users can organize resources under specific topics, engage through a social-interaction layer, and track growth via an integrated analytics dashboard.
</p>

<h2>🛠️ Technical Excellence</h2>
<ul>
  <li><strong>Optimized Backend:</strong> Implemented <b>Server-Side Pagination</b> (6-8 records per request) and <b>Custom DRF Serializers</b> to minimize payload size and improve latency.</li>
  <li><strong>Data Visualization:</strong> Integrated <b>Recharts</b> to provide users with a real-time analytics dashboard for tracking content engagement.</li>
  <li><strong>Security & Auth:</strong> Features <b>Token-based Authentication</b>, protected routes, and custom password reset/update workflows.</li>
  <li><strong>User Autonomy:</strong> Fully developed user settings including profile editing and a secure <b>Account Deletion</b> system with manual string confirmation.</li>
</ul>

<h2>📱 Features</h2>
<table width="100%">
  <tr>
    <td width="50%">✅ <b>12+ Responsive Pages</b> (Desktop/Laptop/Mobile)</td>
    <td width="50%">✅ <b>Topic & Resource Management</b> (Full CRUD)</td>
  </tr>
  <tr>
    <td width="50%">✅ <b>Engagement System</b> (Likes, Dislikes, Comments)</td>
    <td width="50%">✅ <b>Personalized Dashboards</b> for data tracking</td>
  </tr>
  <tr>
    <td width="50%">✅ <b>Public User Profiles</b> to showcase contributions</td>
    <td width="50%">✅ <b>Bootstrap Icons</b> for a polished UI</td>
  </tr>
</table>

<h2>🚀 Installation & Setup</h2>
<pre>
<code>
# Clone the repository
git clone https://github.com/ZohaibKhanDeveloper/CollaborativeResourceHub-Backend
git clone https://github.com/ZohaibKhanDeveloper/CollaborativeResourceHub-Frontend

# Setup Backend (Django)
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

# Setup Frontend (React)
cd frontend
npm install
npm start
</code>
</pre>

<hr />

<div align="center">
  <p>Built with ❤️ by Zohaib | 2026</p>
</div>

<h2>Screenshots Of Project</h2>
<ul>
    <li><h4>Home Page</h4></li>
    <li>This is a simple home page where user can read about the system onsite</li><br>
    <img src="./ProjectScreenShots/Home.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/Home2.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/HomeUnlog.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Topics Page</h4></li>
    <li>This page Shows all the topics for public user where thay can see and find the solutions fo his/her own problems</li><br>
    <img src="./ProjectScreenShots/Topics.PNG" alt="Image">
</ul>
<ul>
    <li><h4>About Page</h4></li>
    <li>This page just shows about the developer information.</li><br>
    <img src="./ProjectScreenShots/About.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Login Page</h4></li>
    <li>This page created for the user (which are already registered) for login to the system.</li><br>
    <img src="./ProjectScreenShots/Login.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Register Page</h4></li>
    <li>This page created for the users to register and collaborate in the plateform.</li><br>
    <img src="./ProjectScreenShots/Register.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Topic Page (With Resources)</h4></li>
    <li>This page will be shown when a user click on the topic title. This page lists all the resources created for this topic along with the resource's likes, dislikes, comments, date, time etc. Also if the logged in user click then he/she can create a resource for this topic can also comment and can like or dislike other resources as well.</li> <br>
    <img src="./ProjectScreenShots/TopicPage.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/TopicPage2.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Public User Profile Page</h4></li>
    <li>This page will be appear when a user click on the username in the topic page. The page lists all the detail of the user which can explain the reputation of the user in the plateform for other users. It lists all the topics he/she created all the resources and all the count of likes,dislikes,comments etc.</li> <br>
    <img src="./ProjectScreenShots/PublicUser.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Logged In User Dashboard Page</h4></li>
    <li>When a user Successfully logged in to the system then he/she will be redirected to the dashbaord page where he/she can check thier activity my moving forward year details and back year details with line charts and one pie chart shows the count of likes dislikes and comments in total. Buttons are present to check each year detail monthly detail or activity for topics creation and resource collaboration.</li> <br>
    <img src="./ProjectScreenShots/Dashboard.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Logged In User Topics Page</h4></li>
    <li>
        User page where he can edit or delete his/her topics with proper forms and buttons. A user can also create new topics for the problem he/she facing.
    </li> <br>
    <img src="./ProjectScreenShots/UserTopics.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/UserTopics2.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Logged In User Resources Page</h4></li>
    <li>
        User page where he can edit or delete his/her resources he/she created for other user's topics with proper forms and buttons.
    </li> <br>
    <img src="./ProjectScreenShots/UserResources.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/UserResources2.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/UserResources3.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Logged In User Votes Page</h4></li>
    <li>
        User page where he can edit or delete his/her likes/dislikes he/she created for other user's resource ratings with proper buttons.
    </li> <br>
    <img src="./ProjectScreenShots/UserVotes.PNG" alt="Image"> <br>
</ul>
<ul>
    <li><h4>Logged In User Comments Page</h4></li>
    <li>
        User page where he can edit or delete his/her comments he/she created for other user's resource ratings with proper buttons and forms.
    </li> <br>
    <img src="./ProjectScreenShots/UserComments.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/UserComments2.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Logged In User Profile Settings Page</h4></li>
    <li>
        User page where he can edit/change/update or delete his/her accounts with proper buttons and forms.
    </li> <br>
    <img src="./ProjectScreenShots/UserSettings.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/UserSettings2.PNG" alt="Image">
</ul>
<ul>
    <li><h4>Following are some of the above pages but shows responsivness for small screens like mobile</h4></li>
    <img src="./ProjectScreenShots/ResponsiveHome2.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/ResponsiveHome.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/LoginRes.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/LogoutPageResp.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/Registerresp.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/UnloggedInResp.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/UserResourcesResp.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/VotesResp.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/UserSettingsResp.PNG" alt="Image"> <br>
    <img src="./ProjectScreenShots/UserSettingsResp2.PNG" alt="Image">
</ul>