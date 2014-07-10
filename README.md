## Validating App Manifests from Testing Participants 

note: leave all 

### Prepare a Participant's App Manifest:

1. **Replace** the manifest.webapp in this directory with the participant's manifest.webapp

2. In the participant's manifest.webapp, **change**:

* launch_path to "/manifest_testing/index.html"

* icon paths to "/manifest_testing/img/icon-128.png" and "/manifest_testing/img/icon-60.png"

* developer url for the German locale to "http://de.ezoehunt.github.io/manifest_testing"


### Validate the App Manifest

1. [Validate the manifest][1] as a hosted app. Use this App Manifest url<br/>: http://ezoehunt.github.io/manifest_testing/manifest.webapp

2. Click to see the full Validation Report.

3. Save the Validation Report with the participant's App Manifest file. Use same names on each, so we don't get them mixed up.


### Tests We've Run
* 07/09/14 - Users were asked to create an App Manifest for a fictional app. To create the App Manifest, they were given [these app details][2] and a link to [the instructions on MDN][3].



[1]: https://marketplace.firefox.com/developers/validator

[2]: http://brampitoyo.github.io/sample-marketplace-app/find-my-friends.html

[3]: https://developer.mozilla.org/en-US/Apps/Build/Manifest