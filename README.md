## Validating App Manifests from Testing Participants 

Depending on the test's fictional app, you may need to validate the App Manifest as a hosted app or as a packaged app. Instructions below for both.

Note: You don't need to do anything with the app structure or directories. The only file you'll be dealing with is the manifest.webapp 

### Validate App Manifest for Hosted Fictional App

1. Copy files from the gh-pages branch of this repo.

2. For each validation, **replace** the manifest.webapp with the participant's manifest.webapp

3. In the participant's manifest.webapp, **change**:

* launch_path to "/manifest_testing/index.html"

* icon paths to "/manifest_testing/img/icon-128.png" and "/manifest_testing/img/icon-60.png"

* developer url for the German locale to "http://de.ezoehunt.github.io/manifest_testing"

4. [Validate the manifest][1] as a **hosted** app.

5. Click to see the full Validation Report.

6. Save the Validation Report with the participant's App Manifest file. Use same names on each, so we don't get them mixed up.


### Validate App Manifest for Packaged Fictional App

1. Copy the files from the gh-pages branch of this repo.

2. Zip up the index.html, manifest.webapp, and the /images directory. Avoid validation warnings by zipping via command line. From inside /manifest_testing, type<br/>"zip -r -X foo.zip index.html manifest.webapp images"

2. Upload and [validate the manifest][1] foo.zip as a **packaged** app. 

2. Click to see the full Validation Report.

3. Save the Validation Report with the participant's App Manifest file. Use same names on each, so we don't get them mixed up.


### Tests We've Run
* 07/09/14 - Users were asked to create an App Manifest for a fictional app. To create the App Manifest, they were given [these app details][2] and a link to [the current instructions on MDN][3].



[1]: https://marketplace.firefox.com/developers/validator

[2]: http://brampitoyo.github.io/sample-marketplace-app/find-my-friends.html

[3]: https://developer.mozilla.org/en-US/Apps/Build/Manifest