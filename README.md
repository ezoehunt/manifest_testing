## Validating App Manifests from Testing Participants 

note: leave all 

### Prepare a Participant's App Manifest:

1. **Replace** the manifest.webapp in this directory with the participant's manifest.webapp

2. In the participant's manifest.webapp, **change**:

* launch_path to "/manifest_testing/index.html"

* icon paths to "/manifest_testing/img/icon-128.png" and "/manifest_testing/img/icon-60.png"

* developer url for the German locale to "http://de.ezoehunt.github.io/manifest_testing"


### Validate the App Manifest

1. [Validate the manifest here][1].

2. Click to view the Full Validation Report.

3. Screenshot the report. 

4. Save the Validation Report with the participant's App Manifest. Use same names on each, so we don't get them mixed up.


### Tests We've Run
* 07/09/14 - Users were asked to create an App Manifest for a fictional app. To create the App Manifest, they were given <a href="http://brampitoyo.github.io/sample-marketplace-app/find-my-friends.html">these app details</a> and a link to <a href="https://developer.mozilla.org/en-US/Apps/Build/Manifest">the instructions on MDN</a>.

[1]: https://marketplace.firefox.com/developers/validator