---
title: MariaDB
layout: post
permalink: /mariadb
category: db
releasePolicyLink: https://mariadb.org/about/maintenance-policy/
changelogTemplate: https://mariadb.com/kb/en/mariadb-__LATEST_SHORT_HAND__-changelog/
activeSupportColumn: false
releaseDateColumn: true
auto:
  git: https://github.com/MariaDB/server.git
  regex: ^mariadb-(?<major>0|[1-9]\d*)\.(?<minor>0|[1-9]\d*)\.(?<patch>0|[1-9]\d*)$
command: mysqld --version
eolColumn: Support Status
sortReleasesBy: 'releaseCycle'
releases:
-   releaseCycle: "10.7"
    release: 2021-11-08
    eol: 2023-02-14
    latest: "10.7.3"
    latestShortHand: "1073"
    latestReleaseDate: 2022-02-12
-   releaseCycle: "10.6"
    release: 2021-04-23
    eol: 2026-07-06
    latest: "10.6.7"
    latestShortHand: "1067"
    latestReleaseDate: 2022-02-12
-   releaseCycle: "10.5"
    release: 2019-11-25
    eol: 2025-06-24
    latest: "10.5.15"
    latestShortHand: "10515"
    latestReleaseDate: 2022-02-12
-   releaseCycle: "10.4"
    release: 2018-11-08
    eol: 2024-06-18
    latest: "10.4.24"
    latestShortHand: "10424"
    latestReleaseDate: 2022-02-12
-   releaseCycle: "10.3"
    release: 2017-04-13
    eol: 2023-05-25
    latest: "10.3.34"
    latestShortHand: "10334"
    latestReleaseDate: 2022-02-12
-   releaseCycle: "10.2"
    release: 2016-04-16
    eol: 2022-05-23
    latest: "10.2.43"
    latestShortHand: "10243"
    latestReleaseDate: 2022-02-12
-   releaseCycle: "10.1"
    release: 2014-07-01
    eol: 2020-10-17
    latest: "10.1.48"
    latestShortHand: "10148"
    latestReleaseDate: 2020-10-30
-   releaseCycle: "10.0"
    release: 2012-11-11
    eol: 2019-03-31
    latest: "10.0.38"
    latestShortHand: "10038"
    latestReleaseDate: 2019-01-29
-   releaseCycle: "5.5"
    release: 2012-04-10
    eol: 2020-04-11
    latest: "5.5.68"
    latestShortHand: "5568"
    lts: true
    latestReleaseDate: 2020-05-06

---

> [MariaDB](https://mariadb.org/about/) is a community-developed, commercially supported fork of the MySQL relational database management system (RDBMS).

A new MariaDB Server version will be announced for General Availability approximately once a year. The MariaDB Foundation guarantees that every release will be maintained for at least 5 years.

The MariaDB Foundation may decide to maintain selected releases beyond the normal 5 years if they are in exceptionally widespread use. As MariaDB 5.5 is included in multiple prominent Linux distributions with a lifespan beyond 2017, the Foundation is committed in maintaining it until 2020.

These dates constitute the public policy of the MariaDB Foundation and are not legally binding. The software is released with the GPL license as-is, without warranties.
