# Code pipeline provenance

**singing a helm chart:**
helm package --sign --key ${helm_signing_key} --keyring ./${path_to}/secring.kbx ${chart-name}

