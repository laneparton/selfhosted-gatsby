<p align="center">
  <a href="https://www.gatsbyjs.com">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Selfhosted Gatsby Resources
</h1>
<p align="center">A collection of resources for those of us that host Gatsby outside of the standard providers like Gatsby Cloud, Netlify, Vercel, etc.</p>

<h2>Plugins</h2>
<ul>
    <li><a href="https://github.com/gatsby-uc/plugins/tree/main/packages/gatsby-plugin-fastify">gatsby-plugin-fastify</a> - A way to integrate your Gatsby site with a Node.js server using Fastify. Enables Functions, DSG, SSR, Image CDN, etc.</li>
    <li><a href="https://github.com/jariz/gatsby-plugin-s3">gatsby-plugin-s3</a> - Enables you to deploy your gatsby site to a S3 bucket.</li>
</ul>

<h2>Gatsby Documentation</h2>
<ul>
    <li><a href="https://www.gatsbyjs.com/docs/debugging-incremental-builds/">Debugging Incremental Builds</a> - Dive into how incremental builds work and how you can debug them.</li>
    <li><a href="https://www.gatsbyjs.com/docs/multi-core-builds/">Multi-core Builds</a> - Control the CPU consumed by your build process with `GATSBY_CPU_COUNT`.</li>
    <li><a href="https://www.gatsbyjs.com/docs/how-to/performance/resolving-out-of-memory-issues/#increase-allocated-memory-andor-upgrade-your-hardware">Increase allocated memory</a> - Control your Node memory usage with `NODE_OPTIONS=--max-old-space-size`.</li>
</ul>

<h2>Gatsby Issues</h2>
<ul>
    <li><a href="https://github.com/gatsbyjs/gatsby/issues/12817">Dynamically build pages in lambda environment</a> - Brief discussion on building Gatsby in AWS Lambda functions.</li>
    <li><a href="https://github.com/gatsbyjs/gatsby/issues/14366">Add a gatsby cli api</a> - Brief look at the Gatsby CLI and how one might use it to call functions programmatically.</li>
</ul>

<h2>Cloud Hosting</h2>
<ul>
    <li><a href="https://dev.to/mikeyglitz/developing-a-nextjs-app-on-openfaas-oof">Developing a NextJS app on OpenFaaS</a> - Self-hosting with OpenFaaS (Serverless Kubernetes). Next.js - but still useful to compare.</li>
    <li><a href="https://medium.com/netlify/migrating-netlifys-continuous-deployment-infra-to-kubernetes-and-everything-we-learned-along-the-1e5989254269">Migrating Netlify’s Continuous Deployment infra to Kubernetes (and everything we learned along the way)</a> - A deep dive in the work Netlify did to move onto Kubernetes.</li>
    <li><a href="https://www.reddit.com/r/devops/comments/u7vzzl/how_do_you_think_vercelnetlify_implement_their/">How do you think Vercel/Netlify implement their preview URL feature?</a> - An interesting look at the infrastructure behind preview URLs.</li>
    <li><a href="https://www.reddit.com/r/nextjs/comments/s4xeg5/who_here_is_working_on_something_hosted_somewhere/">Who here is working on something hosted somewhere other than Vercel or Netifly?</a> - A relevant thread on alernative hosting options.</li>    
</ul>

<h3>Cloud Hosting - Tools</h3>
<ul>
    <li><a href="https://docs.meli.sh/">Meli Docs</a> - Meli is an open source platform built for deploying static sites and frontend applications. Unclear how well maintained it is, but still interesting nonetheless.</li>
    <li><a href="https://github.com/fission/fission">Fission: Serverless Functions for Kubernetes</a> - Fission is a fast serverless framework for Kubernetes with a focus on developer productivity and high performance.</li>
</ul>

<h3>Cloud Hosting - Webhooks</h3>
<ul>
    <li><a href="https://docs.aws.amazon.com/amplify/latest/userguide/webhooks.html">Incoming webhooks</a> - Documentation on AWS Amplify webhooks, which may be useful in deploying content changes from your CMS.</li>
    <li><a href="https://developers.cloudflare.com/pages/platform/deploy-hooks/">Cloudflare Deploy Hooks</a> - With Deploy Hooks, you can trigger deployments using event sources beyond commits in your source repository.</li>
    <li><a href="https://github.com/DymytriiLynx/gatsby-webhooks">gatsby-webhooks</a> - An open-source implementation of Build webhooks using Express.js</li>
    <li><a href="https://medium.com/technogise/auto-build-gatsby-application-using-custom-webhook-on-wordpress-c3c5f70ca005#3c90">Auto build Gatsby application using custom Webhook on Wordpress</a> - An interesting write-up with a real example of a Java (Springboot) webhook.</li>
    <pre>
      - https://www.twilio.com/blog/create-wordpress-plugin-rebuild-gatsby-app-aws-github-actions
      - https://humanoids.nl/en/articles/sanity-webhook-github/
      - https://mxd.codes/articles/how-to-deploy-your-gatsby-site-on-your-own-server
  </pre>
</ul>

<h3>Cloud Hosting - Webhooks</h3>
<ul>
</ul>

<h2>Blog Posts & Articles</h2>
<ul>
    <li><a href="https://valenciandigital.com/insights/why-containerize-your-gatsby-application">Why Containerize Your Gatsby Application?</a> - A quick tutorial on containerizing Gatsy + NGINX.</li>
    <li><a href="https://www.digitalocean.com/community/tutorials/how-to-deploy-a-gatsby-application-to-digitalocean-app-platform">How to Deploy a Gatsby Application to DigitalOcean App Platform</a> - Deploy Gatsby to DigitalOcean's PaaS, App Platform.</li>
    <li><a href="https://humanoids.nl/en/articles/sanity-webhook-github/">Automatically rebuilding Gatsby websites using a webhook</a> - Build your own Express.js webhook to authenticate and trigger a GitHub pipeline.</li>
    <li><a href="https://moonmeister.net/blog/gatsby-incremental-builds-the-backstory/">Gatsby Incremental Builds: The Backstory</a> - An unique perspective into Gatsby Incremental builds written by Alex Moon.</li>
</ul>

<h2>Videos</h2>
<ul>
    <li><a href="https://www.youtube.com/watch?v=khydpJc3iFE">Gatsby JS | Continuous deployment with AWS Amplify</a> - Deploy a Gatsby JS website to AWS Amplify.</li>
</ul>

<hr style="margin: 32px 0;"/>

<h2>To be sorted...</h2>
<pre>
- https://dockerquestions.com/2020/12/07/kaniko-how-to-cache-folders-from-gatsby-build-in-kubernetes-using-tekton/
- https://www.reddit.com/r/nextjs/comments/q7vw6p/cheaper_vercel_alternatives_specifically_to/
- https://www.reddit.com/r/nextjs/comments/qwa8m8/is_it_possible_to_deploy_a_nextjs_app_with_ssr/
- https://github.com/netlify/gatsby-runner#how-it-works (https://www.netlify.com/blog/cut-build-times-with-gatsby-runner/)
- https://www.jameshill.dev/articles/running-gatsby-within-aws-lambda/
  - https://github.com/jahilldev/gatsby-lambda/blob/main/src/lambda.ts
- https://gist.github.com/digitalkaoz/94933c246ba67032a1507083e2605a30
- https://stackoverflow.com/questions/66762442/gatsby-preview-server-in-a-serverless-stateless-environment
</pre>
