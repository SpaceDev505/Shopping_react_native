<p align="center">
<a href="https://ibb.co/2ZYMmwT"><img src="https://i.ibb.co/g4FWHGx/image00001.jpg" alt="image00001" border="0"></a>
</p>

### React Native Expo.

</br>

</br>

## Features

- Light/dark mode toggle
- Copying System appearance
- Login and Register Screens
- Settings Screen
- Bottom Tab Navigator
- Cross platform

</br>


</br>

## Setting Up

To run this project using Expo, you can download it as a zip or clone this repo, then run

```bash
  npm i
  npx expo start
```
If you have an emulator you can run the app on it, or you can download the Expo Go app on your phone, make sure you're connected to the same network as your computer, and scan the code from the camera app. It might take a while to load initially.

Whenever you want to release android/ios builds, run:

```bash
  npx expo prebuild
```


</br>

## Documentation

## Contributing

Please take a moment to review this document in order to make the contribution
process easy and effective for everyone involved.

Following these guidelines helps to communicate that you respect the time of
the developers managing and developing this open source project. In return,
they should reciprocate that respect in addressing your issue or assessing
patches and features.

<a name="bugs"></a>
### Bug reports

A bug is a _demonstrable problem_ that is caused by the code in the repository.
Good bug reports are extremely helpful - thank you!

Guidelines for bug reports:

1. **Use the GitHub issue search** &mdash; check if the issue has already been
   reported.

2. **Check if the issue has been fixed** &mdash; try to reproduce it using the
   latest `master` or development branch in the repository.

3. **Isolate the problem** &mdash; make sure that the code in the repository is
_definitely_ responsible for the issue.

A good bug report shouldn't leave others needing to chase you up for more
information. Please try to be as detailed as possible in your report.


<a name="features"></a>
### Feature requests

Feature requests are welcome. But take a moment to find out whether your idea
fits with the scope and aims of the project. It's up to *you* to make a strong
case to convince the Roots developers of the merits of this feature. Please
provide as much detail and context as possible.


<a name="pull-requests"></a>
### Pull requests

Good pull requests - patches, improvements, new features - are a fantastic
help. They should remain focused in scope and avoid containing unrelated
commits.

**Please ask first** before embarking on any significant pull request (e.g.
implementing features, refactoring code), otherwise you risk spending a lot of
time working on something that the developers might not want to merge into the
project.

Please adhere to the coding conventions used throughout the project (indentation,
comments, etc.).

Adhering to the following this process is the best way to get your work
merged:

1. [Fork](http://help.github.com/fork-a-repo/) the repo, clone your fork,
   and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>//React-Native-Light-Dark-Starter
   # Navigate to the newly cloned directory
   cd /React-Native-Light-Dark-Starter
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/<upsteam-owner>//React-Native-Light-Dark-Starter
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout <dev-branch>
   git pull upstream <dev-branch>
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Commit your changes in logical chunks. Please adhere to these [git commit
   message guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   or your code is unlikely be merged into the main project. Use Git's
   [interactive rebase](https://help.github.com/articles/interactive-rebase)
   feature to tidy up your commits before making them public.

5. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream <dev-branch>
   ```

6. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

10. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/)
    with a clear title and description.


