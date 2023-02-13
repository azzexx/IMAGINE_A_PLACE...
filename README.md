# IMAGINE_A_PLACE...
...where you can handful of friends can spend time together. A place that makes it easy to talk every day and hang out more often.
[![Netlify Status](https://api.netlify.com/api/v1/badges/b2603b06-e161-4a8c-840b-7eb23676b6b0/deploy-status)](https://app.netlify.com/sites/gatsbyjs-netlify-cms-ultimate-portfolio/deploys)

### Intended for intermediate to advanced audiences

<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.drteresavasquez.com">
    <img alt="Dr. Teresa Vasquez" src="https://www.drteresavasquez.com/wp-content/uploads/2017/02/dr-teresa-vasquez.png" width="125"/>
  </a>
</p>
<h1 align="center">
  Dr. Teresa Vasquez - Portfolio Pro App
</h1>

- [Get Started](#get-started)
- [Set up your machine](#set-up-your-machine)
- [Repo Setup](#repo-setup)
- [Connect GitHub and Netlify](#connect-github-and-netlify)
- [Optional Integrated App Sections](#optional-integrated-app-sections)
  - ["Portfolio" App](#portfolio-app)
  - ["Get Placed" App](#get-placed-app)
  - ["Volunteer Up" App](#volunteer-up-app) <b>(COMING SOON!)</b>
  - ["Mentorship" App](#mentorship-app) <b>(COMING SOON!)</b>

<hr>

## Know before you get started
This Open source project was created for software developers. This template will not be totally usable to individuals who do not know how to use React, GatsbyJS, GraphQL and/or SASS. 

If you understand the basic premise behind software development, this is a good spring board into React.

## Get Started
There are a couple of parts to get your site up and ready to use GatsbyJS with Netlify CMS using JSON as the data type to feed to GraphQL.

By cloning this repo, everything is set up, you just need to make sure that your machine is ready and you know how to make the connections with [Netlify](https://app.netlify.com/) - not to be confused with Netlify CMS.

### Set up your machine
- [Gatsby](https://www.gatsbyjs.org/tutorial/part-zero/)
- Get up to speed with [Netlify CMS](https://www.netlifycms.org/docs/start-with-a-template/)

### Repo Setup
- Clone the repo
```
gatsby new {SITE-NAME} git@gitlab.com:drteresavasquez/gatsbyjs-netlify-cms-ultimate-portfolio.git
cd {SITE-NAME}
git init
npm i
```
- Create a repo on GitHub or GitLab and follow steps to connect code
```
git add -A
git commit -m "first repo commit"
git remote add origin {NEWLY-CREATED-REPO}
git push -u origin master
```

### Connect GitHub/GitLab and Netlify
- Understand the [GatsbyJS/Netlify connection](https://www.gatsbyjs.org/docs/deploying-to-netlify/#git-repository-setup)
- [Set up application](https://github.com/settings/developers) - select OAuth and create application. 
- Use creds to set up [Netlify OAuth](https://app.netlify.com/sites/drteresavasquez/settings/access#oauth)

<hr>

## Optional Integrated App Sections

### Portfolio App
- [Documentation](portfolio.md)

The portfolio app helps devs streamline their projects lists into a seamless set of info blocks. It is recommended that devs also create a blog post for maximum exposure.

### "Get Placed" App
- [Documentation](getPlaced.md)

The Get Placed App is an addition to this website. It allows users who are job searching to create separate resumes for each position they are applying for. 

It also generates a link to share the resume, has a print CSS stylesheet so that it prints properly, and has a resume tracking section in the admin of the application.

You can also create multiple template layouts for different types of jobs for which you are applying. The resumes are mobile friendly as well.

It also creates a page of resumes for the user to view the status of each, which is maintained in the NetlifyCMS backend. You can password protect this page for your own viewing.

<hr>

### "Volunteer Up" App
- [Documentation](volunteer.md)

I created this section of the application because I dedicate specific time for volunteering and I wanted to keep track of my hours while also showing that I am committed in my community to anyone who wanted info or check out some of the places I have volunteered. 

I offer a brief description of what I did, the contact email of the individual I did work with as well as information on the origanization via a brief bio and link to their website.

<hr>

### "Mentorship" App
- [Documentation](mentorship.md)

I have several mentors and mentees and sometimes it is hard to keep track of what you spoke about or action items from your conversations. This small interface allows you to not only keep track, but also hold yourself accountable by following through.

It also creates a page of mentorship activity for the user to view the status of each, which is maintained in the NetlifyCMS backend. You can password protect this page for your own viewing.

