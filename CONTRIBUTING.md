# Contributing to z-wave-blobs

All types of contributions are encouraged and valued. 

## How to contribute assets

There should be only one module (or multiple binaries for various arch) per pull request.

- Notice file should accompany the binaries
  (markdown file matching filename pattern is recommended),
  Please give as many details as possible:
  Why is it contributed as binary and not source code?
  or any hints on context,
  this will be appreciated for further investigation.
- License file must be present:
  to the contributor's best knowledge, the legal terms should align to the source code that generated the asset,
  or terms of previous distribution of asset.
- Two issues should be created to track the impact of this contribution:
  - The first one in the z-wave-blob repository
    to request an alternative and suppress imported binary file
  - The second one in the project
    that will consume z-wave-blobs to request the removal of this tainting dependency.
- For finer tracking, more context can be added in the git-footer.
  using "Origin: URL" field which can be human and machine readable
  (eg: Origin: https://{company}/#{project}/{revision} if not public).
