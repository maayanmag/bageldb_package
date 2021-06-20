# How to update the bageldb dart package
1. **Autentication**
Go to [pub.dev](pub.dev) site, and sign in to a user that have the premmisions to the package (actually is only me - Maayan - for this moment). Maybe you'll need to sign in via the CLI too.
2. **Edit the package**
After you finish to edit the package, change version in ```pubspec.yaml``` file. Use [this](https://semver.org/spec/v2.0.0-rc.1.html) and [that](https://dart.dev/tools/pub/versioning) rule to select the right version. Offcoures you should add another additional pacakges that you use them in your update.
Now, go to the ```CHANGELOG.md``` file, add a new section with the name of the version, and the cahnges that you made. Use the form that already wrote on the previous versions. **Notice: if you don't update the version number, the update will not be accepted!** 
3. **Push the changes**
Now you can publish the new version. Make sure you installed Flutter CLI. Now, to test the version upload, run this command: ```dart pub publish --dry-run```. It should give you a feedback. 
If everthing is alright, you can now run ```dart pub publish```, and voila!
If you faced any problems, read [here](https://dart.dev/tools/pub/publishing) about the proccess.
