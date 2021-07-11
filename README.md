# Redwood

## Purpose

To try out this lovely new jamstack.

## Personal Experience

It is too powerful, little buggy sometimes but pretty easy to get hang of, future can be quiet bright if developers keep up the amazing work. I made this full stack app with most of it auto code generation features. Still I would not recommend it to use in production right now. Provides easy deployments too.

I would not be continuing with the tutorial or any project with this right now but in future definitely will.

Uses Netlitfy and Vercel for deployment,
Netlify for Auth & Rail.app for Postgresql

Has ReactJS in front end with graphql with apollo in the backend.

> **WARNING:** RedwoodJS software has not reached a stable version 1.0 and should not be considered suitable for production use. In the "make it work; make it right; make it fast" paradigm, Redwood is in the later stages of the "make it work" phase.

## Getting Started

- [Tutorial](https://redwoodjs.com/tutorial/welcome-to-redwood): getting started and complete overview guide.
- [Docs](https://redwoodjs.com/docs/introduction): using the Redwood Router, handling assets and files, list of command-line tools, and more.
- [Redwood Community](https://community.redwoodjs.com): get help, share tips and tricks, and collaborate on everything about RedwoodJS.

### Setup

We use Yarn as our package manager. To get the dependencies installed, just do this in the root directory:

```terminal
yarn install
```

### Fire it up

```terminal
yarn redwood dev
```

Your browser should open automatically to `http://localhost:8910` to see the web app. Lambda functions run on `http://localhost:8911` and are also proxied to `http://localhost:8910/.redwood/functions/*`.
