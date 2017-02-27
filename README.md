# DDF Distributions

This is an attempt to update the methods for producing the ddf distribution of
karaf using the `karaf-assembly` goal of the `karaf-maven-plugin`

## Goals

At a minimum recreate the standard ddf distribution zip that is built as part of the official project

Additional goals include:

* Packaging multiple distributions (similar to what karaf does)
  * minimal
  * standard
  * enterprise
* Clean up method for overriding/branding dist contents
  * properties files should be edited with the `karaf-maven-plugin` if possible
  * any additional files that are supported should be edited instead of copied over
  * investigate packaging of "beta" features into a dev distribution/feature repo


## Tasks

- [ ] Create standard distribution
- [ ] Create minimal distribution
- [ ] create enterprise distribution
- [ ] create dev distribution/feature repo
- [ ] migrate to editing karaf prop files
- [ ] verify features install correctly (some dependencies fail to resolve currently)
