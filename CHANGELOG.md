# CHANGELOG

## v2.0.0

Major change : AWS SDK dependency was upgragred to 2.6, see migration guide at bottom of README to upgrade from v1.
Feature : Add wait_for_invalidation task (#32) @exoszajzbuk
Improvement : Simpler way to set deployment_path (#33) @j15e

## v1.2.0

Feature : Add exclusions (#30) @exoszajzbuk

## v1.1.0

Feature : Add support for Cloudfront invalidations (#29) @exoszajzbuk

## v1.0.0

Major change : drop support for ruby < 2.1 
Add option to upload only gzipped files (#27)

## v0.3.0

Feature:     Add Capistrano 3.x support (#17)
Improvement: Set correct headers for ".gz" files. (#21)

## v0.2.11

Updated signing certificate.

## v0.2.10 (never published)

Bugfix : loading issue (#18) @yhourdel

## v0.2.9

Bugfix : fix gemspec dependencies

## v0.2.8 (yanked)

Improvement : lock dependency to Capistrano v2 for current version
Improvement : Update spec for new AWS SDK

## v0.2.7

Bugfix : support non-standard file extensions. (#14) @barvaz

## v0.2.6

Feature : Adds ability to specify redirect location for files. (#13) @aledovsky
Feature : Adds S3 endpoint selection option. (#11) @aledovsky
Improvement : Require fileutils to support newer rubies. (#10) @douglasjarquin
Bugfix : Pass a string to the content_type option (#11) @douglasjarquin
