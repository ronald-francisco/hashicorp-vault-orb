# HashiCorp Vault Orb [![CircleCI Build Status](https://circleci.com/gh/jmingtan/hashicorp-vault-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/jmingtan/hashicorp-vault-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/jmingtan/hashicorp-vault)](https://circleci.com/orbs/registry/orb/jmingtan/hashicorp-vault) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/jmingtan/hashicorp-vault-orb/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

A CircleCI orb for working with HashiCorp Vault in your build pipeline.

![Vault Logo](https://raw.githubusercontent.com/jmingtan/hashicorp-vault-orb/main/docs/Vault_PrimaryLogo_Black.png)

## Usage

See the [orb registry listing](https://circleci.com/orbs/registry/orb/jmingtan/hashicorp-vault) for usage guidelines.

## Resources

[HashiCorp Vault](https://www.vaultproject.io) - A tool for secrets management, encryption as a service, and privileged access management.

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/<namespace>/<project-name>) - The official registry page of this orb for all versions, executors, commands, and jobs described.

[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.

### How to Contribute

We welcome [issues](https://github.com/<organization>/<project-name>/issues) to and [pull requests](https://github.com/<organization>/<project-name>/pulls) against this repository!

### How to Publish
* Create and push a branch with your new features.
* When ready to publish a new production version, create a Pull Request from _feature branch_ to `main`.
* The title of the pull request must contain a special semver tag: `[semver:<segment>]` where `<segment>` is replaced by one of the following values.

| Increment | Description|
| ----------| -----------|
| major     | Issue a 1.0.0 incremented release|
| minor     | Issue a x.1.0 incremented release|
| patch     | Issue a x.x.1 incremented release|
| skip      | Do not issue a release|

Example: `[semver:major]`

* Squash and merge. Ensure the semver tag is preserved and entered as a part of the commit message.
* On merge, after manual approval, the orb will automatically be published to the Orb Registry.


For further questions/comments about this or other orbs, visit the Orb Category of [CircleCI Discuss](https://discuss.circleci.com/c/orbs).

