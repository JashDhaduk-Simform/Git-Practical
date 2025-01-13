<h1>Git Exercise :</h1>

<h3>1) Create a new repository with a template :</h3>
<ul>
  <li>login to GitHub account.</li>
  <li>Click on New to create repository. Select whatever is needed from repo details they asked.</li>
  <li>After creating repo marked it as "Template Repository" from Settings to enable template functionalities.</li>
  <li>Using template repository will enables user to use the same structure of repo in their new repo.</li>
</ul>
<img src="https://github.com/JashDhaduk-Simform/Git-Practical/blob/main/Screenshots/Screenshot%20from%202025-01-13%2011-02-49.png" alt="Screenshot" width="500"/>
<img src="https://github.com/JashDhaduk-Simform/Git-Practical/blob/main/Screenshots/Screenshot%20from%202025-01-13%2011-03-04.png" alt="Screenshot" width="500"/>
<img src="https://github.com/JashDhaduk-Simform/Git-Practical/blob/main/Screenshots/Screenshot%20from%202025-01-13%2011-03-26.png" alt="Screenshot" width="500"/>
<img src="https://github.com/JashDhaduk-Simform/Git-Practical/blob/main/Screenshots/Screenshot%20from%202025-01-13%2011-03-12.png" alt="Screenshot" width="500"/>

<h3>2) Initialize git-flow :</h3>
<pre>
  <code>
    git flow init
  </code>
</pre>
<ul>
  <li>Run the above command to initialize the git flow model.</li>
  <li>After initializing git flow   2 base branches is created as : develop and main</li>
</ul>


<h3>3) Create a feature branch for project setup with the proper Zoho task ID (example: TP2-T1299_Project_Setup) :</h3>
<pre>
  <code>
    git checkout -b feature/abc
  </code>
</pre>
<ui>
  <li>Above command will create the new branch for adding feature in the project.</li>
</ui>

<h3>4) Create a sub-branch from the project setup branch and perform squash, reset, rebase and cherrypick ​​​​​.</h3>
<pre>
  <code>
    git checkout feature/abc
  </code>
</pre>
<li>Above code will now points towards the "feature/abc" branch.</li>
<pre>
  <code>
    git cheackout -b feature/sub_abc
  </code>
</pre>
<li>Above code will create the sub branch of "feature/abc" branch as "feature/sub_abc" branch.</li>
<li>Until this; that many branches are created as shown below :</li>
<img src="https://github.com/JashDhaduk-Simform/Git-Practical/blob/main/Screenshots/Screenshot%20from%202025-01-13%2010-55-04.png" alt="Screenshot" width="500"/>
