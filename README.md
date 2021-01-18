<p align="center">
  <a href="https://cara.lekoarts.de">
    <img alt="LekoArts" src="https://img.lekoarts.de/gatsby/gatsby-site-illustration.png" />
  </a>
</p>
<h1 align="center">
  Gatsby Starter Portfolio: Cara
</h1>

<p align="center">
  <a href="https://github.com/LekoArts/gatsby-starter-portfolio-cara/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-0BSD-blue.svg" alt="Gatsby Starter Portfolio: Cara is released under the 0BSD license." />
  </a>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  <a href="https://twitter.com/intent/follow?screen_name=lekoarts_de">
    <img src="https://img.shields.io/twitter/follow/lekoarts_de.svg?label=Follow%20@lekoarts_de" alt="Follow @lekoarts_de" />
  </a>
</p>

Playful and Colorful One-Page portfolio featuring Parallax effects and animations. Using the Gatsby Theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-cara).

## Portfolio link : 
https://jc-man-567165.netlify.app

## 🚀 Getting Started

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/LekoArts/gatsby-starter-portfolio-cara) [![Edit gatsby-starter-portfolio-cara](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/LekoArts/gatsby-starter-portfolio-cara/tree/master/)

1. **Create a Gatsby site.**

Use the Gatsby CLI to create a new site, specifying this project

```sh
gatsby new project-name https://github.com/LekoArts/gatsby-starter-portfolio-cara
```

2. **Start developing.**

Navigate into your new site's directory and start it up.

```sh
cd project-name
gatsby develop
```

# Editing the content

The content of the page is managed by .mdx files inside the theme's sections folder. You can edit the files by shadowing them in your site.

These files are available: intro.mdx, projects.mdx, about.mdx, contact.mdx

See the example that shadows via src/@lekoarts/gatsby-theme-cara/sections/intro.mdx:

### Changing content

The content of this project is defined in four `.mdx` files inside the theme's `sections` folder. You can override the files `intro.mdx`, `projects.mdx`, `about.mdx` and `contact.mdx`. This starter has overriden the `intro.mdx` file as an example. Place the other files in the same `src/@lekoarts/gatsby-theme-cara/sections/` folder.

You have to use the `<ProjectCard />` component inside `projects.mdx` to display the cards. Example:

```md
## Projects

<ProjectCard
  title="Memories"
  link="https://github.com/car251290/myMemories"
  bg="linear-gradient(to right, #1b6b96  0%, #FBB03B 100%)"
>
<ProjectCard
  title="Template Chooser"
  link="https://github.com/car251290/Template-Chooser"
  bg="linear-gradient(to right, #1b6b96  0%, #FBB03B 100%)"
>
 Web Application build with JavaScript to get a Templates stored in Sharepoint and display
  it and inserted to a Word document.
</ProjectCard>
```
### 🌟 General
- **For most developers, I recommend starting with the [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

### Netlify DNS
Add a domain
You can add a domain to Netlify DNS by registering a new domain or by delegating an existing domain from another registrar.

At Netlify  React in production and are familiar with the challenges in deploying it to production as well. 

## Powerful Netlify

Today Facebook announced their opinated boiler-plate for getting React projects started. This is great news, since the ecosystem around getting React projects started has been in a state of Flux (see what I did there?).

Register a new domain
To learn how to register a new domain, visit the domain registration page.

Collect form submissions
Netlify supports automatic collection of form submissions for any HTML form on your site, with no database required. Trigger an email, slack notification, or webhook with each form submission.

## Icon for my page
there is process I will design my icon.
and to publish my icon: https://www.favicon-generator.org

# Add a domain you own
To add a domain you have already registered elsewhere:

Go to your team’s Domains page and select Add or register domain.
Enter the domain you wish to add and select Verify.
You will be asked to confirm that you are the owner of the domain. Select Yes, add domain to create a Netlify DNS zone for the domain.
You will be given the option to add DNS records, followed by instructions to delegate your domain to Netlify.




