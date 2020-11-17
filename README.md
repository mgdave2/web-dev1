# Make Your Own Website

1. To get started, you'll first need to create a GitHub account, which can be done [here](https://github.com/join).

2. Next, you'll need to make a copy of this repository on your own account. To do so, click on `Use this template` (see top right corner of the image below).

![Use this template](https://gyazo.com/5dbc23abce2b8e11e745cfea306a65df.png)
  
3. Fill out the information with a repository name of your choice (this example will use `webdev-intro-workshop`). Make sure to make the repository public.

![Filling out template](https://gyazo.com/8396278322e5225b936450b3e8081681.png)

4. After your repository is generated, go to the `Settings` tab (right side of the picture below).

![Settings](https://gyazo.com/66a2155b507b355213e4c4ccb515885f.png)

5. Scroll down to the `GitHub Pages` section, change `Source` to `main` (you can leave the `/ (root)` as is) and hit `Save`.

![GitHub Pages](https://gyazo.com/882be6469cf6581c3dc6c46cc49bc5f7.png)

6. This template is now ready to be hosted on GitHub pages, and you should see a link in the `GitHub Pages` section of settings. It may not work immediately, but after a few minutes you should see the results of the template at the specified URL.

![GitHub Pages URL](https://gyazo.com/bcb91f9b69b2c423a2e60ff7af6a9f49.png)

7. Now that we've got GitHub pages working, you'll need to set up a [CodeSandbox](https://codesandbox.io/) account. Navigate to the [sign-in page](https://codesandbox.io/signin) and hit `Sign in with GitHub`. After signing in with your GitHub, you'll be redirected to your account dashboard.

8. From the dashboard, click on `New Sandbox`. Switch to the `Import Project` tab and enter the GitHub URL (for example, <https://github.com/arpanlaha/webdev-intro-workshop>) of the repository you just created. Hit `Import and Fork` to generate your sandbox.

![New Sandbox](https://gyazo.com/62aa6ce8d806c77ec13e4eb28ba321a7.png)

![Import Project](https://gyazo.com/62aa6ce8d806c77ec13e4eb28ba321a7.png)

9. You'll now have copies of all the files from the template in CodeSandbox. As you make any edits, you'll be able to see the changes reflected on the right-hand panel.

10. Click on the GitHub logo on the left-hand vertical navigation bar (third from the bottom in the screenshot below) and hit `Sign in`.

![GitHub logo](https://gyazo.com/020011e2c45c3ff7833706d67666b908.png)

11. After signing in, hit `Link Sandbox` in the same menu pane to link the sandbox you're working on to the repository you just created.

![Link Sandbox](https://gyazo.com/9e900b701da239095b956c42becf1ad7.png)

12. You can now make changes in your sandbox and push them to your repository, from which they'll be deployed to GitHub pages. Let's test this out.

13. Switch back to the filesystem view (second icon below my profile picture in the screenshot below) and go to `index.html`.

![filesystem view](https://gyazo.com/903e16f8a8339b4ed12f7c7037e30eeb.png)

14. On line 11, after `Hello world!`, add some more text (`Test` in the example) and save using your operating system's shortcut (Ctrl-s or Cmd-s). You should see this reflected on the right.

![Add test](https://gyazo.com/cec5faefb287afba64adb727a0c8f97b.png)

15. Navigate back to the GitHub menu pane (where we linked our sandbox). Add a short description of your changes to the `Summary` input (not the `Optional description`), and hit `Commit Changes`. If you then navigate to your GitHub repository, you'll see your changes have been pushed. After a few minutes, you'll also see your changes reflected in the deployed GitHub Pages URl we made in step 6.

![Commit changes](https://gyazo.com/2be0c7f3c7086adbeac05c5987d8b42a.png)

16. You're now ready to start building your own personal website!

## Your GitHub Pages URL

You'll notice that the deployed website will be hosted at `<username>.github.io/<repository name>`, or `arpanlaha.github.io/webdev-intro-workshop` in our example. If you want to host a website at your GitHub Pages root, or just `<username>.github.io`, create a repository with the name `<username>.github.io` and follow steps 4-6 from above to enable GitHub Pages.
