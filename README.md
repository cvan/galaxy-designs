# galaxy-designs

Designs for [galaxy](https://github.com/cvan/galaxy).

# v1

## Home

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/1.%20galaxy%20home@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/1.%20galaxy%20home@2x.png)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | UI | Implement UI for homepage | [@yangshun](https://github.com/yangshun) | [cvan/galaxy#127](https://github.com/cvan/galaxy/issues/127) | |

## Game detail page

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/2.%20galaxy%20detail@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/2.%20galaxy%20detail@2x.png)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | UI | Implement image gallery for videos and screenshots | [@yangshun](https://github.com/yangshun) | [cvan/galaxy#40](https://github.com/cvan/galaxy/issues/40) | | previous design started
v0 | UI | Redesign game detail page per mocks | [@yangshun](https://github.com/yangshun) | [cvan/galaxy#86](https://github.com/cvan/galaxy/issues/86) | [cvan/galaxy#94](https://github.com/cvan/galaxy/pull/94) | merged
v0 | UI | Hook up game detail page with real data | | [cvan/galaxy#119](https://github.com/cvan/galaxy/issues/119) | |
v0 | API | Update game API endpoints to handle Number of Players | | [cvan/galaxy-api#131](https://github.com/cvan/galaxy-api/issues/131) | |
v0 | UI | Update game detail page to show Number of Players | | [cvan/galaxy#120](https://github.com/cvan/galaxy/issues/120) | |
v0 | API | Create an API endpoint to record game purchase/install | [@scottmeng](http://github.com/scottmeng) | [cvan/galaxy-api#128](https://github.com/cvan/galaxy-api/issues/128) | | merged
v0 | UI | "Play" button should record game purchase/install | [@scottmeng](http://github.com/scottmeng) | [cvan/galaxy#117] (https://github.com/cvan/galaxy/issues/117) | | merged
v1 | UI | Send hash of client's feature compatibilities to API | | [cvan/galaxy#118](https://github.com/cvan/galaxy/issues/118) | |
v1 | API | Update game submission/update API endpoints to handle browser requirements | | [cvan/galaxy-api#129](https://github.com/cvan/galaxy-api/issues/129) | |
v1 | API | Exclude games that are incompatible for a user's device | | [cvan/galaxy-api#130](https://github.com/cvan/galaxy-api/issues/130) | |

## API documentation

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/3.%20galaxy%20api@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/3.%20galaxy%20api@2x.png)

[@scottmeng](http://github.com/scottmeng) has written a version of our docs using this amazing docs service called [Apiary](http://apiary.io):

&nbsp;&nbsp;&nbsp;&nbsp;__http://docs.galaxy.apiary.io/__

Everyone is encouraged to update the docs as we make adjustements to the API. Please sign up for an [Apiary account](http://apiary.io/) and tell [@cvan](http://github.com/cvan) the email address you used for your account so he can add you to the group.

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | UI/API | Documentation for REST API | [@scottmeng](http://github.com/scottmeng) | [cvan/galaxy-api#112](https://github.com/cvan/galaxy-api/issues/112) | [docs.galaxy.apiary.io](http://docs.galaxy.apiary.io/) | done

## Feedback modal

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/4.%20galaxy%20feedback@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/4.%20galaxy%20feedback@2x.png)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | API | Implement potato captcha for feedback modal |  | [cvan/galaxy-api#160](https://github.com/cvan/galaxy-api/issues/160) |  | 
v0 | API | Send email when feedback is received |  | [cvan/galaxy-api#140](https://github.com/cvan/galaxy-api/issues/140) |  | 
v0 | API | Create an API endpoint to POST feedback | [@at-kevinlau](https://github.com/at-kevinlau) | [cvan/galaxy-api#123](https://github.com/cvan/galaxy-api/issues/123) | [cvan/galaxy-api#159](https://github.com/cvan/galaxy-api/pull/159) | in review
v0 | UI | Implement feedback modal | [@yangshun](https://github.com/yangshun) | [cvan/galaxy#105](https://github.com/cvan/galaxy/issues/105) | [cvan/galaxy#111](https://github.com/cvan/galaxy/pull/111) | merged

## Game submission

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/5.%20galaxy%20game%20submission@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/5.%20galaxy%20game%20submission@2x.png)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | UI | Use aviary for resizing, cropping, uploading icon uploads | [@cvan](http://github.com/cvan) | [cvan/galaxy#49](https://github.com/cvan/galaxy/issues/49)<br>[cvan/galaxy#98](https://github.com/cvan/galaxy/issues/98)  | [cvan/galaxy#115](https://github.com/cvan/galaxy/issues/115) | merged
v0 | UI | Hook up file upload + aviary cropping for screenshots | [@birkanu](http://github.com/birkanu) | [cvan/galaxy#129](https://github.com/cvan/galaxy/issues/129) | |
v0 | UI | Fix icon upload bug when icon is updated | | [cvan/galaxy#130](https://github.com/cvan/galaxy/issues/130) | |
v0 | UI | Store images on disk upon submission | | [cvan/galaxy-api#30](https://github.com/cvan/galaxy-api/issues/30) | |
v0 | UI | Redesign game submission/edit pages per mocks | [@birkanu](https://github.com/birkanu)<br>[@yangshun](https://github.com/yangshun) | [cvan/galaxy#98](https://github.com/cvan/galaxy/issues/98) | | in progress
v0 | UI | Limit media uploads to 25 MB | | [cvan/galaxy#128](https://github.com/cvan/galaxy/issues/128) | |
v0 | API | Limit media uploads to 25 MB | | [cvan/galaxy-api#133](https://github.com/cvan/galaxy-api/issues/133) | |
v0 | UI | Update game submission/edit API endpoints to accept JSON blob | [@soedar](https://github.com/soedar)<br>[@yangshun](https://github.com/yangshun) | [cvan/galaxy-api#118](https://github.com/cvan/galaxy-api/pull/118) | | merged
v1 | UI | Add drag-and-drop support for file uploads | | [cvan/galaxy#131](https://github.com/cvan/galaxy-api/issues/131) | |

## Game edit page

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/6.%20galaxy%20game%20edit@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/6.%20galaxy%20game%20edit@2x.png)

See [issues above](#game-submission).

## Developer dashboard

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/7.%20galaxy%20developer%20dashboard@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/7.%20galaxy%20developer%20dashboard@2x.png)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | UI | Implement UI for Developer Dashboard (My Games) | [@CharlesChong](https://github.com/CharlesChong) | [cvan/galaxy#99](https://github.com/cvan/galaxy/issues/99) | [cvan/galaxy#109](https://github.com/cvan/galaxy/pull/109) | in review
v0 | API | Filter games by developer userID | [@CharlesChong](https://github.com/CharlesChong) | [cvan/galaxy-api#150](https://github.com/cvan/galaxy-api/issues/150) | [cvan/galaxy-api#153](https://github.com/cvan/galaxy-api/pull/153) | merged |

## Reviewer dashboard

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/8.%20galaxy%20reviewer%20dashboard@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/8.%20galaxy%20reviewer%20dashboard@2x.png)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | UI | Implement basic UI for Reviewer Dashboard | [@aricha](https://github.com/aricha) | [cvan/galaxy#15](https://github.com/cvan/galaxy/issues/15) | [cvan/galaxy#83](https://github.com/cvan/galaxy/pull/83) | merged
v0 | UI | Add status drop-down menu to Reviewer Dashboard | [@aricha](https://github.com/aricha) | [cvan/galaxy#121](https://github.com/cvan/galaxy/issues/121) | |
v0 | UI | Add buttons to view/edit/delete/disable game from Reviewer Dashboard | [@aricha](https://github.com/aricha) | [cvan/galaxy#122](https://github.com/cvan/galaxy/issues/122) | |
v0 | UI | Tweaks to the Reviewer Dashboard table | [@aricha](https://github.com/aricha) | [cvan/galaxy#123](https://github.com/cvan/galaxy/issues/123) | |

## Curation dashboard

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/9.%20galaxy%20curation%20dashboard@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/9.%20galaxy%20curation%20dashboard@2x.png)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | UI | Implement basic UI for Curation Dashboard | [@emoore24](https://github.com/emoore24) | [cvan/galaxy#124](https://github.com/cvan/galaxy/issues/124) | [cvan/galaxy#113](https://github.com/cvan/galaxy/pull/113) | in review
v0 | UI | Add ability to drag-and-drop sort list of featured apps in Curation Dashboard | [@emoore24](https://github.com/emoore24) | [cvan/galaxy#125](https://github.com/cvan/galaxy/issues/125) | |
v0 | API | Send back game objects from featured endpoint | [@emoore24](https://github.com/emoore24) | | [cvan/galaxy-api#132](https://github.com/cvan/galaxy-api/pull/132) | in review

## Curation modal

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/10.%20galaxy%20curation%20submission@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/10.%20galaxy%20curation%20submission@2x.png)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | UI | Implement basic UI for Curation Modal | | [cvan/galaxy#126](https://github.com/cvan/galaxy/issues/126) | |
v0 | UI | Add client-based game searching for the curation modal | [@rchreptyk](https://github.com/rchreptyk) | [cvan/galaxy#108](https://github.com/cvan/galaxy/issues/108) | [cvan/galaxy#110](https://github.com/cvan/galaxy/issues/110) | in review, WIP

## User settings

[![](https://raw.github.com/cvan/galaxy-designs/master/v1/11.%20galaxy%20user%20settings@2x.png)](https://raw.github.com/cvan/galaxy-designs/master/v1/11.%20galaxy%20user%20settings@2x.png)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | UI | Beautify User Settings page | [@scottmeng](http://github.com/scottmeng) | [cvan/galaxy#112](https://github.com/cvan/galaxy/issues/112) | [cvan/galaxy#114](https://github.com/cvan/galaxy/issues/114) | done

## Tests

![](http://f.cl.ly/items/0b0L171F2g0f3c2H430B/Image%202014.03.10%201%3A49%3A26%20AM.gif)

Milestone | Type | Task | Assignee | Issue | Pull request | Status
--------- | ---- | ---- | -------- | ----- | ------------ | ------
v0 | API | Investigate testing | [@soedar](http://github.com/soedar) | [cvan/galaxy-api#124](https://github.com/cvan/galaxy-api/issues/124) | | in progress
v0 | UI | End-to-end tests | [@scottmeng](http://github.com/scottmeng) | [cvan/galaxy#48](https://github.com/cvan/galaxy/issues/48) | | in progress
