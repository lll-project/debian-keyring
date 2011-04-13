Introduction
============

This repository contains the debian source package for lll-project-keyring.
These GPG keys are used to sign lll Debian packages. The point of contact for
the lll project is Bryce Lelbach (wash) <blelbach@cct.lsu.edu>.

Build
=====

You will need the dpkg-buildpackage and gnupg to build a Debian package from
this repository. The invocation is:::

  dpkg-buildpackage -kBUILDER_KEY_ID

Where BUILDER_KEY_ID is your GPG key id.

