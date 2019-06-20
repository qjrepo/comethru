Basiclly used Jenkins to do the automation.
Installed jenkins on a azure linux machine
Set up the integration between github and jenkins using webhooks this allows every build for jenkins project 
when execute git push
And then also using publish over ssh on jenkins to deploy web app to a aws ec2 instance and also run the app on the instance automatically
For each update in source, run git add . , git commit and git push, and abort the previous jenkins build,the web site will update itself automatically for the end user
