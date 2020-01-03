---
title: Managing the collections and their sections
date: 2020-01-03T14:04:25.066Z
author: dferber
modifiedDate: null
description: "Learn how to edit your Help Center's content."
---

_This tutorial will show you how to set up your own help center. At the end, you will have the help center running locally. The next section then shows how to edit the content. And the final step shows how to deploy the help center to the internet, so that anyone can access it._

### Install the gatsby-cli

Install the [`gatsby-cli`](https://www.npmjs.com/package/gatsby-cli) if you don't have it already.

```shell
npm install --global gatsby-cli
```

If you don't have `npm` either, install [node.js](https://nodejs.org/en/) first.

### Create a new Gatsby site

Create a new Gatsby site, using `gatsby-starter-help-center` as the template.

```shell
gatsby new help-center https://www.github.com/dferber90/gatsby-starter-help-center
```