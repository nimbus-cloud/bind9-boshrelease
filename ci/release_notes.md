# Improvements

- Zone masters can now be overridden on a per-zone basis

- This BOSH release now supports BOSH v2-style links, for
  connecting master and slave jobs for things like IP lookups,
  replication allowances, acls, zone listings, etc.

- The templates/-style of manifests has been replaced with the
  newer manifests/-style.  You should be able to deploy a test
  version of this release using manifests/bind9.yml.
