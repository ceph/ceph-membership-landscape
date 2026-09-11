# Ceph Foundation Membership Landscape

This landscape displays the current [Ceph Foundation](https://ceph.io) member organizations and their membership tiers. Member data is synced nightly from [LFX](https://lfx.linuxfoundation.org/).

## View the Landscape

**[https://landscape.cephfoundation.org/](https://landscape.cephfoundation.org/)**

## How It Works

- **Data source:** Member organizations and tiers are pulled from LFX via [lfx-landscape-tools](https://github.com/jmertic/lfx-landscape-tools).
- **Site generation:** The static site is built with [landscape2](https://github.com/cncf/landscape2).
- **Automation:** A nightly GitHub Action syncs member data and opens a PR if anything changed. Merging the PR triggers a rebuild and deploy to GitHub Pages.

## Embedding

To embed the landscape on another website, visit the [embed setup page](https://landscape.cephfoundation.org/ceph-membership-landscape/embed-setup) to generate an iframe snippet.

## Corrections

Information should be corrected via LFX.

## License

This repository is licensed under the [Apache License, Version 2.0](LICENSE). Project and company logos are copyrighted by their respective owners and are cached here for display purposes.
