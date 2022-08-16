# Sauce Labs Quick Start

### `Mobile Beta Testing Edition`  
_Powered by TestFairy™_

<br>

_This source code is licensed under the MIT license found in the LICENSE file in the root directory of this source tree._

<br>
<img align="right" src="assets/logo-sauce.png">  



| :rocket: [Sign Up for a _free_ trial at Sauce Labs][00] :bangbang:       |
|:-------------------------------------------------------------------------|
| :page_facing_up: [Mobile Beta Testing Documentation][200]                |
| :page_facing_up: [Mobile Beta Testing API][201]                          |
| :page_facing_up: [Onboarding Video (5 Minutes)][210]                     |
| :page_facing_up: [My Demo App (SDK Reference Implementation)][300]       |
||
| :page_facing_up: _`saucelabs`_ [Documentation Home][10]                  |
| :page_facing_up: _`saucelabs`_ [Knowledge Base][11]                      |





<br>
<br>

# 

```shell
repoURL="https://github.com/kmissoumi/sauce-101-beta-testing"
release="orange-0.0.1"

# clone repo
git clone ${repoURL} && cd sauce-101-beta-testing

# download my demo app
curl --get --location ${repoURL}/releases/download/${release}/my-demo-app.apk --output apps/my-demo-app.apk
curl --get --location ${repoURL}/releases/download/${release}/my-demo-app.ipa --output apps/my-demo-app.ipa

# upload and populate build
export TESTFAIRY_ACCESS_KEY=""
./buildEnv
```

