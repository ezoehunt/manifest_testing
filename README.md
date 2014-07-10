## Validating App Manifests from Testing Participants 

### Use this app structure to test App Manifests created by testing particpants.

To validate a participant's App Manifest:
1. Replace the manifest.webapp with the participant's manifest.webapp

2. In the participant's manifest.webapp, change:
* launch_path to "/manifest_testing/index.html"
* icon paths to "/manifest_testing/img/icon-128.png" and "/manifest_testing/img/icon-60.png"
* developer url for the German locale to "http://de.ezoehunt.github.io/manifest_testing"

### Tests We've Run
* 07/09/14 - Users were asked to create an App Manifest for a fictional app. To create the App Manifest, they were given <a href="http://brampitoyo.github.io/sample-marketplace-app/find-my-friends.html">these app details</a> and a link to <a href="https://developer.mozilla.org/en-US/Apps/Build/Manifest">the instructions on MDN</a>.

</html>