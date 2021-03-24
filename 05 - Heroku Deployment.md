# HEROKU
> is a container-based cloud Platform as a Service (PaaS). Developers use Heroku to deploy, manage, and scale modern apps.
> Heroku is fully managed, giving developers the freedom to focus on their core product without the distraction of maintaining servers, hardware, or infrastructure. The Heroku experience provides services, tools, workflows, and polyglot support—all designed to enhance developer productivity.

![](https://leanpub.com/site_images/howtodeployagowebapptoheroku101/cloudcomp.png)

## Getting Started on Heroku with Node.js
- The Heroku CLI requires Git
- Command Line Interface (CLI). You use the `CLI` to manage and scale your applications.
- Use the `heroku login` command to log in to the Heroku CLI: *This command opens your web browser to the Heroku login page*

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQdFFzXERUKZD5S9FbzLlrqZcmP-mSPh18bMw&usqp=CAU)

1. Prepare the app
```
git clone https://github.com/heroku/node-js-getting-started.git
cd node-js-getting-started
```
2. Deploy the app
```
heroku create
Creating sharp-rain-871... done, stack is heroku-18
http://sharp-rain-871.herokuapp.com/ | https://git.heroku.com/sharp-rain-871.git
Git remote heroku added
```
> Heroku generates a random name (in this case sharp-rain-871) for your app, or you can pass a parameter to specify your own app name.

3.  git push heroku main `git push heroku main`


