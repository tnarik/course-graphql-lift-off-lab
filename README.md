# Odyssey Lift-off Lab

Welcome to the companion app of Odyssey Lift-off Lab! You can [find the lab's instructions on Odyssey](https://odyssey.apollographql.com/lift-off-lab), Apollo's learning platform.

You can [preview the completed demo app here](https://lift-off-client-demo.netlify.app/).

> **Note**
>
> The original repo is [here](https://github.com/apollographql/odyssey-lift-off-lab), and it might have been updated since following the course.
>
> To keep it up to date:
> ```
> git remote add upstream https://github.com/apollographql/odyssey-lift-off-lab
> git fetch upstream
> git diff main..upstream/main --name-only # shows files that diverge
> git pull --rebase upstream main
> git push -f
> ```
>
> I like creating a branch before this rebases, so that I can understand (perhaps more easily) the delta. I name them as `solution_<YYYY><MM><DD>`. This is because this repo is not a "fork", but an implementation/solution on top of the course.
>
> Additional updates would merit additional branches, which are then merged on top of "main"
>

## How to use this repo

The lab outlines the requirements for this challenge. This codebase is the starting point of your journey!

There are 3 main folders:

- `server`: The starting point of our GraphQL server.
- `client`: The starting point of our React application.
- `final`: The final stage of both the server and client folders, with all of the steps and code completed!

To get started, open up a Terminal window.

1. Navigate to the `server` folder.
1. Run `npm install`.
1. Run `npm start`.

This will start the GraphQL API server.

In another Terminal window,

1. Navigate to the `client` folder.
1. Run `npm install`.
1. Run `npm start`.

This will open up `localhost:3000` in your web browser.

## Getting Help

For any issues or problems concerning the course content, please refer to the [Odyssey topic in our community forums](https://community.apollographql.com/tags/c/help/6/odyssey).
