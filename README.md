# A02
Spring 2025 IS117-004


<h2>Glossery Definition</h2>
<br>
<b>Branch</b> - a new/separate version of the main repository.<br>
<b>Clone</b> - a full copy of a repository, including all logging and versions of files.<br>
<b>Commit</b> - keep track of our progress and changes as we work. Git considers each commit change point or "save point"<br>
<b>Fetch</b> - downloads commits, files, and refs from a remote repository into your local repository<br>
<b>GIT</b> - Tracking code changes, Tracking who made changes, Coding collaboration<br>
<b>Github</b> - web-based platform that allows developers to store, share, and collaborate on code<br>
<b>Merge</b> - combine multiple sequences of commits into one unified history<br>
<b>Merge</b> Conflict - when two or more versions of a file have conflicting changes, and a system cannot automatically determine which changes to keep<br>
<b>Push</b> - used to upload local repository content to a remote repository<br>
<b>Pull</b> - used to upload remote repository to a local repository<br>
<b>Remote</b> - a common repository that all team members use to exchange their changes<br>
<b>Repository</b> - a virtual storage space for a project's code and files, and the history of changes made to them<br>

<br>
<h2>Tutorial on setting up git/webstorm/github</h2>
GitHub<br>
<ol>
<li>Create an account or login to https://github.com<br></li>
<li>In the top right, click the + an choose "New Repository"<br></li>
<li>Name it based off what you wish for it to be<br></li>
  <li>Check "Add a README file"<br></li>
  <li>Click "Create Repository"<br></li>
</ol>

Git<br><br>
Git Stages
<ol>
<li>Working Directory</li>
<li>Staging</li>
<li>Local Repo (commits)</li>
</ol>
Common Git Commands
<ol>
  <li>git add</li>
  <li>git commit</li>
  <li>git push</li>
  <li>git pull</li>
</ol>
Keep local and remote in sync to reduce merge conflicts<br>
<strong>Note</strong>: Generally when you're done with a branch after it's been merged you  don't go back to it
<ol>Future branches typically stem from the destination branch or some other brnach used for grouping purposes</ol>

Webstorm<br>
<ol>
<li>Install WebStorm from JetBrains.</li>
<li>Open Settings → Version Control → Git, set the Path to Git (e.g., /usr/bin/git or C:\Program Files\Git\bin\git.exe).</li>
<li>Enable "Commit Automatically on Save" (optional for auto-commit).</li>
<li>Go to Preferences → Version Control → GitHub, and log in with GitHub credentials or use a token.</li>
<li>Enable Git integration: Open VCS → Enable Version Control Integration, then select Git.</li>
</ol>
