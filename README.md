## HTML Files
* [Updated MDN Manifest Instructions - 07/17/14][5]


## Validating App Manifests from Testing Participants 

Depending on the test's fictional app, you may need to validate the App Manifest as a hosted app or as a packaged app. Instructions below for both.

### Validate App Manifest for Hosted Fictional App

Copy files from the gh-pages branch of this repo.

For each App Manifest you want to validate:

- **replace** the manifest.webapp with the participant's manifest.webapp

- change launch_path to "/manifest_testing/index.html"

- change icon paths to "/manifest_testing/img/icon-128.png" and "/manifest_testing/img/icon-60.png"

- change developer url for the German locale to "http://de.ezoehunt.github.io/manifest_testing"

[Validate the manifest][1] as a **hosted** app.

Click to see the full Validation Report.

Save the Validation Report with the participant's App Manifest file. Use same names on each, so we don't get them mixed up.


### Validate App Manifest for Packaged Fictional App

Copy the files from the gh-pages branch of this repo.

Zip up the index.html, manifest.webapp, and the /images directory. Avoid validation warnings by zipping via command line. From inside /manifest_testing, type<br/>"zip -r -X foo.zip index.html manifest.webapp images"

Upload and [validate the manifest][1] foo.zip as a **packaged** app. 

Click to see the full Validation Report.

Save the Validation Report with the participant's App Manifest file. Use same names on each, so we don't get them mixed up.


### Tests We've Run
* 07/09/14 - Users were asked to create an App Manifest for a fictional app. To create the App Manifest, they were given [these app details][2] and a link to [the current instructions on MDN][3]. This test was run twice.

* 07/13/14 - Users were asked to create an App Manifest for a fictional app. To create the App Manifest, they were given [these app details][4] and a link to [the current instructions on MDN][3]. 



[1]: https://marketplace.firefox.com/developers/validator

[2]: http://brampitoyo.github.io/sample-marketplace-app/find-my-friends.html

[3]: https://developer.mozilla.org/en-US/Apps/Build/Manifest

[4]: http://ezoehunt.github.io/manifest_testing/instructions.html

[5]: http://ezoehunt.github.io/manifest_testing/mdn_instructions.html