---
title: "How I used an Astro theme to make this blog"
description: "This post describes the steps I took to make this Astro blog with a theme."
publishDate: "19 Jan 2024"
tags: ["guide", "blog"]
draft: true
---

## Why Astro?

If, like me, you want to share your software projects, learning, or insights through a blog, your first instict likely would have been to code it up from scratch yourself. It was mine.

I wanted to build it at the software level and deploy it under my subdomain.

However this would have shifted the effort into making the blog, later the maintenance of the code, with little time to write.

On the other hand I didn't want to opt for a no code solution, since I want to have software level control of the layout and functionality.

A great middleground I found was to use the Astro framework with a template. It's very quick to set up yet still flexible.

I was able to build out this blog, make basic modifications, and deploy in one night by using a template.

Now I'm able to focus on writing and still make modifications to the code if I choose.

In the next few minutes, I'll walk through the steps I took to set this up. For more information, visit https://astro.build/.

### 1. Choose a theme

Go the Astro website https://astro.build/. On the top navbar, click **Resources** dropdown and click **Themes**. 

Or go to this link: https://astro.build/themes/

Look around the different themes and pick your favorite. For this blog I chose the **Astro Cactus Theme**: https://astro.build/themes/details/astro-cactus/

### 2. Install Astro and theme.

  Click **Get started** on your theme page. This takes you to the github repo of the theme which should have all the info needed to build out your blog. For the rest of this post, I'll be talking about the **Atro Cactus Theme**.

  Navigate to your desired directory and run the following command:

  ```shell
  npm create astro@latest -- --template chrismwilliams/astro-theme-cactus
  ```

  NOTE: If you want to install the packages in the current directory, instead of making a new folder in this directory, run the following command:

  ```shell
  npm create astro@latest -- --template chrismwilliams/astro-theme-cactus ./
  ```

  Follow the prompts. Install the dependencies.