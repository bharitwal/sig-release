---
title: "Kubernetes 1.24 Release Information"
weight: 98
slug: "release"
aliases: [ "/release" ]
description: |
  Information regarding the current release cycle including important dates,
  Release Team contact information, tracking spreadsheets and more!
---

# Kubernetes 1.24

#### Links

* [This document](https://git.k8s.io/sig-release/releases/release-1.24/README.md)
* [Release Team](https://github.com/kubernetes/sig-release/blob/master/releases/release-1.24/release-team.md)
* [Meeting Minutes](http://bit.ly/k8s124-releasemtg) (join [release-team@] to receive meeting invites)
* [v1.24 Release Calendar][k8s124-calendar]
* Contact: [#sig-release] on slack, [release-team@] on e-mail
* [Internal Contact Info] (accessible only to members of [release-team@])

#### Tracking docs

* [Enhancements Tracking Sheet](https://bit.ly/k8s124-enhancements)
* [Feature blog Tracking Sheet](http://bit.ly/k8s124-feature-blog)
* [Bug Triage Tracking Sheet](https://bit.ly/124-bug-triage-tracking)
* [CI Signal Project Board](https://github.com/orgs/kubernetes/projects/11)
* [CI Signal Tracking Log](https://docs.google.com/spreadsheets/d/1ns94ZAH4PIvzhpwU1SGPyl9ek_p4-_Be/)
* [Retrospective Document][Retrospective Document]
* [kubernetes/sig-release v1.24 milestone](https://github.com/kubernetes/kubernetes/milestone/56)

#### Guides

* [Targeting Issues and PRs to This Milestone](https://git.k8s.io/community/contributors/devel/sig-release/release.md)
* [Triaging and Escalating Test Failures](https://git.k8s.io/community/contributors/devel/sig-testing/testing.md#troubleshooting-a-failure)

## TL;DR

The 1.24 release cycle is proposed as follows:

- **Monday 10th January 2022**: Week 1 - Release cycle begins
- **TBC**: Week 2 - [Production Readiness Soft Freeze](https://groups.google.com/g/kubernetes-sig-architecture/c/a6_y81N49aQ)
- **TBC**: Week 3 - [Enhancements Freeze](../release_phases.md#enhancements-freeze)
- **TBC**: Week 11 - [Release Retrospective][Retrospective Document] part 1
- **TBC**: Week 13 - [Code Freeze](../release_phases.md#code-freeze)
- **TBC**: Week 14 - [Test Freeze](../release_phases.md#test-freeze)
- **TBC**: Week 15 - Docs must be completed and reviewed
- **Tuesday 19th April 2022**: Week 15 - Kubernetes v1.24.0 released
- **TBC**: Week 16 - [Release Retrospective][Retrospective Document] part 2
- **TBC**: Week 16 - [Release Retrospective][Retrospective Document] part 3

## Timeline

| **What** | **Who** | **When** | **Week** | **CI Signal** |
|---|---|-------|---|---|
| Start of Release Cycle | Lead | | week 1 | [master-blocking] |
| Start Enhancements Tracking | Enhancements Lead | **TBC** | week 1 | |
| Schedule finalized | Lead | **TBC** | week 1 | |
| Team finalized | Lead | **TBC** | week 1 | |
| Production Readiness Soft Freeze | Enhancements Lead | **TBC** | week 2 | |
| Start Release Notes Draft | Release Notes Lead | **TBC** | week 3 | |
| **Begin [Enhancements Freeze]** ( **Time TBC**) | Enhancements Lead | **TBC** | week 3 | [master-blocking], [master-informing] |
| 1.24.0-alpha.2 released | Branch Manager | **TBC** | Week 4 | |
| 1.24.0-alpha.3 released | Branch Manager | **TBC** | Week 6 | |
| **Begin [Burndown]** (Monday, Wednesday, and Friday meetings) | Lead | **TBC** | week 11 | [1.24-blocking], [master-blocking], [master-informing] |
| **Call for [Exceptions][Exception]** | Lead | **TBC** | week 11 | |
| Brace Yourself, Code Freeze is Coming | Comms / Bug Triage | **TBC** | week 11 | |
| **Begin Feature blog freeze** (**Time TBC**) | Comms Lead | **TBC** | week 11 | |
| 1.24.0-alpha.4 released | Branch Manager | **TBC** | Week 11 | |
| Release retrospective part 1 (**Time TBC**) | Community | **TBC** | week 11 | |
| Burndown Meetings daily| Lead | **TBC** | week 13 | |
| **Begin [Code Freeze]** (**Time TBC**) | Branch Manager | **TBC** | week 13 | |
| 1.24.0-beta.0 released | Branch Manager | **TBC** | week 13 | |
| Docs deadline - Open placeholder PRs | Docs Lead | **TBC** | week 13 | |
| **[Test Freeze]** (**Time TBC**) | Branch Manager | **TBC** | week 14 | |
| Docs deadline - PRs ready for review | Docs Lead | **TBC** | week 14 | |
| 1.24.0-rc.0 released | Branch Manager | **TBC** | week 14 | |
| release-1.24 branch created | Branch Manager | **TBC** | week 14 | |
| release-1.24 jobs created | Branch Manager | **TBC** | week 14 | |
| Start final draft of Release Notes | Release Notes Lead | **TBC** | week 14 | |
| Release blog ready to review (**Time TBC**) | Comms / Docs | **TBC** | week 14 | |
| Docs complete - All PRs reviewed and ready to merge | Docs Lead | **TBC** | week 15 | |
| Feature blogs ready to review (**Time TBC**)| Enhancement Owner / SIG Leads | **TBC** | week 15 | |
| Release Notes complete - reviewed & merged to `k/sig-release` (**Time TBC**) | Release Notes Lead | **TBC** | week 15 | |
| 1.24.0-rc.1 released | Branch Manager | **TBC** | week 15 | |
| **v1.24.0 released** | Branch Manager | **TBC** | week 16 | |
| Release blog published | Comms | **TBC** | week 16 | |
| **[Thaw]** | Branch Manager | **TBC** | week 16 | |
| Release retrospective part 2 (**TBC**) | Community | **TBC** | week 17 | |
| Release retrospective part 3 (**TBC**) | Community | **TBC** | week 17 | |

## Phases

Please refer to the [release phases document](../release_phases.md).

[k8s124-calendar]: https://bit.ly/k8s-release-cal
[Internal Contact Info]: https://bit.ly/k8s124-contacts
[Retrospective Document]: https://bit.ly/k8s124-retro

[Enhancements Freeze]: ../release_phases.md#enhancements-freeze
[Burndown]: ../release_phases.md#burndown
[Code Freeze]: ../release_phases.md#code-freeze
[Exception]: ../release_phases.md#exceptions
[Thaw]: ../release_phases.md#thaw
[Test Freeze]: ../release_phases.md#test-freeze

[release-team@]: https://groups.google.com/a/kubernetes.io/g/release-team
[kubernetes-sig-release@]: https://groups.google.com/forum/#!forum/kubernetes-sig-release
[#sig-release]: https://kubernetes.slack.com/messages/sig-release/
[kubernetes-release-calendar]: https://bit.ly/k8s-release-cal
[kubernetes/kubernetes]: https://github.com/kubernetes/kubernetes

[master-blocking]: https://testgrid.k8s.io/sig-release-master-blocking#Summary
[master-informing]: https://testgrid.k8s.io/sig-release-master-informing#Summary
[1.24-blocking]: https://testgrid.k8s.io/sig-release-1.24-blocking#Summary

[exception requests]: ../EXCEPTIONS.md
[release phases document]: ../release_phases.md