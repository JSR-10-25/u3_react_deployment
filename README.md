# React Heroku Deployment

![React/Heroku](https://img.search.brave.com/IzAeh_TIlWTn4VKa0RMFXKX-hnstcRPdK4peRVjwj4s/rs:fit:1160:600:1/g:ce/aHR0cDovL2Jsb2cu/bG9naWN3aW5kLmNv/bS9jb250ZW50L2lt/YWdlcy8yMDIwLzEw/L2RlcGxveS1yZWFj/dC1hcHAtaGVyb2t1/LmpwZw)

## Objectives

- Deploy react app to Heroku

## Disclaimer

This repo is set up assuming that your apps are stuctured the same way we've done them in class.

## Installing Heroku

Heroku is a hosting site that we'll be using to deploy our project.

Execute the following command in your terminal:

```sh
brew install heroku/brew/heroku
```

The formulae may not be latest, so we'll execute the next command to ensure the latest Heroku version is installed:

```sh
heroku update
```

Once installed, we'll be able to run the necessary commands to deploy our app.

## Signing Up for a Heroku Account

Take this opportunity to head to [Heroku](https://signup.heroku.com/login) and sign up for an account. It's free!

We'll need this later!

## Initializing A Heroku App

In your project folder type in the following command:

```sh
  heroku create
```

This will create a heroku app for you.

Finally we'll add, commit and push our changes to heroku:

```sh
git add .
git commit -m <some message>
git push heroku main
```

The `git push heroku main` will only push the changes to heroku. To push them to github enter the following:

```sh
git push origin main
```

We can monitor what our app is doing with the following command:

```sh
heroku logs --tail
```

## Recap

In this walkthrough, we successfully installed and deployed our React app to Heroku.

## Resources

- [Heroku Docs](https://devcenter.heroku.com/categories/heroku-architecture)
- [Another Way](https://blog.heroku.com/deploying-react-with-zero-configuration)
