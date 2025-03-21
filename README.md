# <p align="center">✨Eventica✨</p>
<!-------------------------------------------------->
<div align="center">
<p>

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Netlify Status](https://api.netlify.com/api/v1/badges/a8c657fc-8eb7-4aa9-b56b-37219cb7bbf8/deploy-status)](https://app.netlify.com/sites/eventica/deploys)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)
![Visitors](https://api.visitorbadge.io/api/visitors?path=Rakesh9100%2FEventica%20&countColor=%23263759&style=flat)
![GitHub forks](https://img.shields.io/github/forks/Rakesh9100/Eventica)
![GitHub Repo stars](https://img.shields.io/github/stars/Rakesh9100/Eventica)
![GitHub contributors](https://img.shields.io/github/contributors/Rakesh9100/Eventica)
![GitHub last commit](https://img.shields.io/github/last-commit/Rakesh9100/Eventica)
![GitHub repo size](https://img.shields.io/github/repo-size/Rakesh9100/Eventica)
![Github](https://img.shields.io/github/license/Rakesh9100/Eventica)
![GitHub issues](https://img.shields.io/github/issues/Rakesh9100/Eventica)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/Rakesh9100/Eventica)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Rakesh9100/Eventica)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/Rakesh9100/Eventica)
</p>
</div>

<!-------------------------------------------------->

<div id="top"></div>

<h2>Table of Contents🧾</h2>

- [Introduction📌](#introduction)
- [Technology Used🚀](#technology-used)
- [Overview⭐](#overview)
- [Getting Started💥](#getting-started)
- [Contributing Guidelines📑](#contributing-guidelines)
- [Code Of Conduct📑](#code-of-conduct)
- [Open Source Programs🥳](#this-repo-has-been-part-of-the-following-open-source-programs)
- [Project Admin⚡](#project-admin)
- [Project Contributors🫂](#project-contributors)
- [Contributing is fun🧡](#contributing-is-fun)
<br>

<!-------------------------------------------------->

<h2>Introduction📌</h2>

Welcome to Eventica, an ultimate guide to the dynamic and diverse events in Bangalore.<br>As the heart of India's tech and cultural hub, Eventica is dedicated to bridging the gap between event organizers and eager participants, creating a vibrant community.

<!-------------------------------------------------->

<h2>Technology Used🚀</h2>

<p>
  <a href="https://www.w3schools.com/html/"> <img src="https://img.icons8.com/color/70/000000/html-5--v1.png" alt="HTML" /></a>
  <a href="https://www.w3schools.com/css/"> <img src="https://img.icons8.com/color/70/000000/css3.png" alt="CSS" /></a>
  <a href="https://www.w3schools.com/js/"><img src="https://img.icons8.com/color/70/000000/javascript--v1.png" alt="JS" /></a>
</p>
<p align="right">(<a href="#top">back to top</a>)</p>

<!-------------------------------------------------->

<h2>Overview⭐</h2>

<h3>Live Project -- (https://eventica.netlify.app)</h3>

<h3>Home/Main Page :-</h3>

![image](https://github.com/user-attachments/assets/e62f056c-726e-4cde-bd73-997cdc0cf37c)<br><br>
<h3>About Page :-</h3>

![image](https://github.com/user-attachments/assets/ec038029-7f7f-496f-a093-8c8e552aeefa)<br><br>
<h3>Upcoming Events Page :-</h3>

![image](https://github.com/user-attachments/assets/c8f22365-d5b6-4325-8d2c-3936601e4d40)<br><br>

<h3>Past Events Page :-</h3>

![image](https://github.com/user-attachments/assets/67f5f2e0-e2bb-455d-83d3-ef2e346d9f2e)<br><br>
<h3>Contact Page :-</h3>

![image](https://github.com/user-attachments/assets/81fdedea-4a46-4b18-9e8d-bda86d4dfed0)
<br><br>
<p align="right">(<a href="#top">back to top</a>)</p>

<!-------------------------------------------------->

<h2>Getting Started💥</h2>

- Fork this Repository.
- Clone the forked repository in your local system.
```
git clone https://github.com/<your-github-username>/Eventica.git
```
- Open `index.html` in your browser.
- View the [Live Project](https://eventica.netlify.app/) here.
- Raise an issue if you find a bug or add a feature.
- Wait for the issue to be assigned and proceed only after the issue is assigned to you.
- Navigate to the project directory.
```
cd Eventica
```
- Create a new branch for your feature.
```
git checkout -b <your_branch_name>
```
- Perfom your desired changes to the code base.
- Track and stage your changes.
```
# Track the changes
git status

# Add changes to Index
git add .
```
- Commit your changes.
```
git commit -m "your_commit_message"
```
- Push your committed changes to the remote repo.
```
git push origin <your_branch_name>
```
- Go to your forked repository on GitHub and click on `Compare & pull request`.
- Add an appropriate title and description to your pull request explaining your changes and efforts done.
- Click on `Create pull request`.
- Congrats! 🥳 You've made your first pull request to this project repo.
- Wait for your pull request to be reviewed and if required suggestions would be provided to improve it.
- Celebrate 🥳 your success after your pull request is merged successfully.
<p align="right">(<a href="#top">back to top</a>)</p>

# Backend Setup Instructions


1. Ensure Node.js and npm are installed on your system. You can verify installation by running:
```
node -v
npm -v
```

2. Navigate to the backend directory:
```
cd server
```

3. Install the required dependencies:
```
npm install
```

4. Create a .env file in the backend root directory and add your environment variables. Here's an example structure:
```
MONGO_URI="mongodb+srv://<your_mongo_db_url>.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0"
SECRET_KEY="THIS_IS_A_JWT_SECRET"
```

5. Start the backend server using nodemon:
```
nodemon api/index.js
```

This will start the server in development mode. By default, it will run on http://localhost:3000.

Test the API endpoints using tools like Postman or Thunder Client.

Now for vercel Deployment:
1. Login into vercel account
2. Click on add project
3. select `server` as root directory
4. add this add env vars
```
MONGO_URI="mongodb+srv://<your_mongo_db_url>.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0"
SECRET_KEY="THIS_IS_A_JWT_SECRET"
```
And server will deployed on vercel

<!-------------------------------------------------->

<h2>Contributing Guidelines📑</h2>

Read our [Contributing Guidelines](https://github.com/Rakesh9100/Eventica/blob/main/.github/CONTRIBUTING_GUIDELINES.md) to learn about our development process, how to propose bugfixes and improvements, and how to build to Eventica.

<!-------------------------------------------------->

<h2>Code Of Conduct📑</h2>

This project and everyone participating in it is governed by the [Code of Conduct](https://github.com/Rakesh9100/Eventica/blob/main/.github/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

<!-------------------------------------------------->

<h2>This repo has been part of the following Open Source Programs🥳</h2>

<table>

<tr>
<td align="center">
<a href="https://iwoc3.live/"><img src="https://github.com/user-attachments/assets/31929aa2-68c1-4621-9a25-85cd2b5a9616" height="140px" width="140px" alt="IWOC2025"></a><br><sub><b>IWOC 2k25</b></sub>
</td>
<td align="center">
<a href="https://www.socialwinterofcode.com/"><img src="https://github.com/user-attachments/assets/5b1d76c0-2345-4425-b90c-3c85cbd9f80d" height="140px" width="180px" alt="SWOC2025"></a><br><sub><b>SWOC 2k25</b></sub>
</td>
</tr>

<tr>
<td align="center">
<a href="https://kwoc.kossiitkgp.org/"><img src="https://github.com/user-attachments/assets/cb303f6e-e912-4618-9f5b-7f36c1b8b3a6" height="140px" width="140px" alt="KWOC2024"></a><br><sub><b>KWOC 2k24</b></sub>
</td>
</tr>

</table>
<p align="right">(<a href="#top">back to top</a>)</p>

<!-------------------------------------------------->

<h2>Project Admin⚡</h2>

<table>
<tr>
<td align="center">
<a href="https://github.com/Rakesh9100/"><img src="https://avatars.githubusercontent.com/u/73993775?v=4" height="140px" width="140px" alt="Rakesh Roshan"></a><br><sub><b>Rakesh Roshan</b><br><a href="https://www.linkedin.com/in/rakesh-roshan-9100/"><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/73993775/278833250-adb040ea-e3ef-446e-bcd4-3e8d7d4c0176.png" width="45px" height="45px"></a></sub>
</td>
</tr>
</table>

<!-------------------------------------------------->

<h2>Project Contributors🫂</h2>

<a href="https://github.com/rakesh9100/eventica/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=rakesh9100/eventica" />
</a>

<!-------------------------------------------------->

<h2>Contributing is fun🧡</h2>

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
<h3>Contributions of any kind from anyone are always welcome🌟!!</h3>
<h3>Give it a 🌟 if you ❤ this project. Happy Coding👨‍💻</h3>
<p align="right">(<a href="#top">back to top</a>)</p>
