# Documentation

<!--- These tags hold related issue numbers. This page's development
is part of #336. --->

## Introduction

- The [ProjectX Overview](/overview) document provides a high-level
  introduction to ProjectX.
  It is a good place to start to learn about the motivation for the project
  and overall design.
  It also has introductions to many of the other topics explored in more
  detail in the other documents.

- The [FAQ](/faq) answers common questions about ProjectX.

## User guide

- The [Signing up a new user](/signup) document describes the process for
  generating keys and registering a user with the ProjectX key server.<!--- #326 #210 --->

- The [ProjectX Access Control](/access_control) document describes
  ProjectX's access control mechanisms. TODO: Break into user-level pieces
  and implementation details; also linked in Architecture below.

- The [ProjectX Configuration](/config) document describes ProjectX's
  configuration file format and settings.

## Tools

- The [`projectx`](https://godoc.org/projectx.io/cmd/projectx) command is a
  command-line tool for creating and administering ProjectX files, users,
  and servers.

- The [`projectx-ui`](https://godoc.org/augie.projectx.io/cmd/projectx-ui) tool
  presents a web interface to the ProjectX name space, and also provides a
  facility to sign up an ProjectX user and deploy an projectxserver to Google Cloud
  Platform.

- The [`cacheserver`](https://godoc.org/projectx.io/cmd/cacheserver)
  is a client-side directory and storage cache for ProjectX.

- The [`projectxfs`](https://godoc.org/projectx.io/cmd/projectxfs) command
  is a [FUSE](https://en.wikipedia.org/wiki/Filesystem_in_Userspace)
  interface for ProjectX.

## Architecture

- The [ProjectX architecture](/arch) page has a number of diagrams
  showing, bottom-up, how the pieces all fit together. TODO: add things like keys,
  sharing etc. as diagrams there.<!---  #217 #209 --->

- The [ProjectX Access Control](/access_control) document describes
  ProjectX's access control mechanisms. TODO: Break into user-level pieces
  and implementation details. TODO: Server-level access control: Writers file etc.

- The [ProjectX Security](/security) document describes ProjectX's security
  model.

## System setup and administration

- The [Setting up `projectxserver`](/server_setup) document explains how
  to set up your own ProjectX installation on a Linux server.<!--- #406 #326 --->

- TODO: Show how to set up with a reverse proxy. <!--- #233 --->

## Programming

- The [`projectx` package](https://godoc.org/projectx.io/projectx) specifies the core
  interfaces that define the ProjectX protocol.

- The [`rpc` package](https://godoc.org/projectx.io/rpc) includes a semiformal
  description of the wire protocol used to communicate between clients and
  servers.

- The [`client` package](https://godoc.org/projectx.io/client) provides a
  simple client interface for communicating with ProjectX servers.

- TODO: A worked example (implementer's guide).
