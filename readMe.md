# How To Submit Homework

You will be submitting your homework using GitHub Classrooms. 
  ### Here are the steps:
- Click on the link to your homework assignment that is posted in the classroom channel.
- That will open up a tab in the browser and will ask you to accept the assignment. Accept it.
  ![Imgur](https://i.imgur.com/6J6ihsn.png)
- That will re-direct you to a different page, here you might need to refresh your browser. Once you refresh it, you should see **You're ready to go!** message. Below this message you will see link to your personal homework repository. Click on it.
  ![Imgur](https://i.imgur.com/HMk9bNb.png)
- Now, that you're redirected to your homework repo, you can check the success by looking at top left. If you see your GitHub handle to the right of the assignment name - success!
  ![Imgur](https://i.imgur.com/JQlbRde.png)
- Click on the `code`, choose `SSH` key and copy it.
- Now open your terminal, `cd` into your homework directory (create one if you don't have it yet) and run `git clone <SSH key>`. That action clones down your remote repository and if you run `ls` from your terminal you should see it right there!
- `cd` into repo that you just cloned down and you are ready to work on your homework!


#### Commands to remember:
- `git add specific_file.txt` will log all changes to the file specific_file.text
- `git add .` will log the changes to all files in the current working directory
- `git add some_dir/` will log the changes to all files in the some_dir directory
- `git add -A` will add all files in the local repo that have been modified
- `git commit -m "any message that is relevant to your changes"`
- `git push origin main` (origin is the nickname of the remote repo.  Main is the name of the branch, this is usually main when you start out)






