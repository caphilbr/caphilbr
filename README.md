# Charlie Philbrook

![GitHub followers](https://img.shields.io/github/followers/caphilbr?style=social)
![GitHub stars](https://img.shields.io/github/stars/caphilbr?style=social)
![Profile views](https://komarev.com/ghpvc/?username=caphilbr&color=blue)

## About Me

I am a full stack software engineer with a background in finance and actuarial science. I love to take complex topics and make them easy for the user to understand and interact with.

## Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/charlie-philbrook)
[![Email](https://img.shields.io/badge/Email-blue?style=flat&logo=gmail&labelColor=blue)](mailto:caphilbr@hotmail.com)

## Skills

- **Languages:** JavaScript, TypeScript, Python, HTML, CSS
- **Frameworks & Tools:** React.js, Express.js, Objection.js, Passport.js, Nodemailer, Dropbox, Git, D3, Numpy, Pandas, SQL, PostgreSQL, Jest, Cypress
- **Other:** Agile Methodologies, Jira, 3rd party API, Actuarial Science (FSA, FCIA)
<p>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/JavaScript.svg" alt="JavaScript" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/TypeScript.svg" alt="TypeScript" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/Python-Dark.svg" alt="Python" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/HTML.svg" alt="HTML" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/CSS.svg" alt="CSS" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/React-Dark.svg" alt="React.js" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/ExpressJS-Dark.svg" alt="Express.js" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/PostgreSQL-Dark.svg" alt="PostgreSQL" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/Git.svg" alt="Git" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/D3-Dark.svg" alt="D3" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://numpy.org/images/logo.svg" alt="Numpy" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Jest.svg" alt="Jest" width="40" height="40"/>
  </picture>
  <picture>
    <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Cypress-Light.svg" alt="Cypress" width="40" height="40"/>
  </picture>
</p>


## Projects

### 1) Allowance & Chore Tracker
[Public Website](https://allowance-chore-tracker-46cd68f48ad0.herokuapp.com/)<br/>
[Repo](https://github.com/caphilbr/allowance-chore-tracker)<br/><br/>
A web app to make family chore tracking and allowance payments easy. Once a parent creates a "family", they send an invite to their children to join via their own user accounts. As a parent, they can setup recurring allowance payments and create & assign chores to children. Each chore has a due date and a dollar value. As a child, they can see their balance and assigned chores. Once a chore is completed, they submit to their parent for approval and payment.

Other notable features include the use of a one-time invite code to invite a child, uploading of profile photos, automatic allowance payments, parental ability to make ad hoc adjustments to child balances, a graphical presentation of a child's balance over time, and a weekly quiz to earn additional money.

The app was built with React, Express, and PostgreSQL (with Knex & Objection). Other technical solutions include Nodemailer for sending email invites, Dropbox for profile photos, Passport for user authentication (including Google login), D3 for charts, a 3rd party API for the quiz, and Cypress tests.<br/><br/>
![screenshot 1](https://github.com/caphilbr/allowance-chore-tracker/blob/main/screen1.jpeg)
![screenshot 2](https://github.com/caphilbr/allowance-chore-tracker/blob/main/screen2.jpeg)

### 2) Auto-Rebalancing Retirement Forecaster
[Repo](https://github.com/caphilbr/retirement-forecaster)<br/><br/>
A web app to determine the sufficiency of your retirement savings. You create a 'Portfolio' which contains your starting balances, age, spending level, etc. You then create a 'Configuration', which tells the app how you want to forecast your savings (e.g., how to determine your annual savings in the future, your target retirement age, how much expenses will drop in retirement, how many scenarios you want to run, etc.). One might imagine running a few different Configurations to see how results are impacted with different inputs.

The app then runs the specified number of projection scenarios. The key result is 'Chance of Fund Exhaustion', which indicates how likely you are to run out of funds before dying! For those interested in the granular results, each scenario can be displayed, along with the year-by-year financial projection.

Other notable features include:
- auto-rebalancing based on age
- dynamic retirement age, pushing off retirement if funds are not sufficient
- asset yields, inflation and salary raises are each dynamically generated each year, based on a mean and standard deviation
- taxes are determined dynamically, using tax brackets and taking into consideration which type of retirement account withdrawals are from
- a choice of savings approach (fixed dollar, % of salary, or salary less expenses & taxes)

The calculation engine was built in Python, with results exposed via a Flask api. The user app was built with React, Express, and PostgreSQL (with Knex & Objection). 

![screenshot 1](https://github.com/caphilbr/retirement-forecaster/blob/main/condensedScreenShot.jpg)

And the more granular results, if interested...
![screenshot 2](https://github.com/caphilbr/retirement-forecaster/blob/main/screenShot2.jpg)

## GitHub Stats

![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=caphilbr&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=caphilbr&layout=compact&theme=radical)
