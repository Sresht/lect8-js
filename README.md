Welcome to Lecture 8!

In this activity, we're going to figure out how to use multiple URLs in Flask.
Then we're going to figure out some basics of Javascript, and adding Javascript
code to HTML apps.

1. Run `git clone https://github.com/Sresht/lect8-js`
2. If you haven't already, go to `https://www.github.com/Sresht/lect7/.bashrc`
   and copy everything from line 75 (# git aliases and functions) to the end
   of the file. Put this in your own .bashrc, and don't forget to run
   `source .bashrc`. Make sure to change line 78 from "Sresht" to your Github
   username.
3. Run `gorigin lect8-js`, which will configure your SSH key to lect8-js.
      If this doesn't work for some reason, run the following:
         `git remote rm origin` &&
         `git remote add origin http://www.github.com/<your-username>/lect8-js`.
4. Go to github and make a new personal repository named lect8-js.
5. Run `git remote -v` and make sure this points to your newly created Github
   repo, and not Sresht's.
6. Now run `git push origin master`. After running `gorigin lect8-js`, you
   should not need to type in your password.
7. Now work with your in-class partners to figure out how to get the app up and
   running. Notice that when you press "Preview Running Application", it will 
   generate an error message!
        Hint: After running app.py, you might need to change the URL in the
        browser window. What do you need to change it to be (read through 
        app.py!)
8. Once you've figured out how to get both URLs running, raise your hand on
   zoom and keep it raised!
9. Finished early? Look into hello.html and index.html and see the different
   ways that you can add Javascript in your html files!
