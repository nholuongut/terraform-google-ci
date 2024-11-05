# GCP Helpers

This module contains helper scripts that automate common GCP tasks:

* `install-gcloud`: This script is meant to be run in a CircleCI job to install the latest version of the Google Cloud SDK CLI tool. Currently, only Ubuntu and Debian are supported.

## Installing the helpers

You can install the helpers using the [nholuongut Installer](https://github.com/nholuongut/nholuongut-installer):

```bash
nholuongut-install --module-name "gcp-helpers" --repo "https://github.com/nholuongut/terraform-aws-ci" --tag "v0.0.1"
```

We recommend running this command in the `dependencies` section of `circle.yml`:

```yaml
dependencies:
  override:
    # Install the nholuongut Installer
    - curl -Ls https://raw.githubusercontent.com/nholuongut/nholuongut-installer/main/bootstrap-nholuongut-installer.sh | bash /dev/stdin --version v0.0.16

    # Use the nholuongut Installer to install the gcp-helpers module
    - nholuongut-install --module-name "gcp-helpers" --repo "https://github.com/nholuongut/terraform-google-ci" --tag "v0.0.1"
```
