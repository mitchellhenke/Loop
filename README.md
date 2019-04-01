# Loop for iOS

# ABOUT THIS BRANCH

This branch is based on the work done here:

https://github.com/LoopKit/Loop/pull/849

https://github.com/LoopKit/Loop/pull/726

https://github.com/LoopKit/LoopKit/pull/246

that add Integral Retrospective Correction and Fat/Protein Unit functionality.


### FPU

Making FPU work in Loop is not straightforward, and is currently something of a workaround.  The FPU changes prompt for grams of carbohydrate, fat, and protein when adding a meal, and converts that into two carbohydrate entries in Loop.  One for the grams of carbohydrates entered on a 2 hour duration, and a second delayed one that converts the fat and protein into carbohydrates in an amount and duration specified by the research linked in the pull request above.  The delay and fat/protein:carbohydrate ratio are configurable.

The above means that when a meal is saved, it will be entirely in carbohydrates, and any reference to the original fat/protein is lost, so editing entered meals is confusing.

![App Icon](/Loop/Assets.xcassets/AppIcon.appiconset/Icon-Small-40%402x.png?raw=true)

[![Build Status](https://travis-ci.org/LoopKit/Loop.svg?branch=master)](https://travis-ci.org/LoopKit/Loop)
[![Join the chat at https://loop.zulipchat.com](https://img.shields.io/badge/zulip-join_chat-brightgreen.svg)](https://loop.zulipchat.com)

Loop is an app template for building an automated insulin delivery system. It is a stone resting on the boulders of work done by many others.

Loop is built on top of [LoopKit](https://github.com/LoopKit/LoopKit). LoopKit is a set of frameworks that provide data storage, retrieval, and calculation, as well as boilerplate view controllers used in Loop.

Please understand that this project:
- Is highly experimental
- Is not approved for therapy

<a href="/Documentation/Screenshots/Phone%20Graphs.png"><img src="/Documentation/Screenshots/Phone%20Graphs.png?raw=true" alt="Screenshot of status screen" width="170"></a>
<a href="/Documentation/Screenshots/Phone%20Bolus.png"><img src="/Documentation/Screenshots/Phone%20Bolus.png?raw=true" alt="Screenshot of bolus screen" width="170"></a>
<a href="/Documentation/Screenshots/Phone%20Notification%20Battery.png"><img src="/Documentation/Screenshots/Phone%20Notification%20Battery.png?raw=true" alt="Screenshot of battery change notification" width="170"></a>
<a href="/Documentation/Screenshots/Phone%20Notification%20Loop%20Failure.png"><img src="/Documentation/Screenshots/Phone%20Notification%20Loop%20Failure.png?raw=true" alt="Screenshot of loop failure notification" width="170"></a>
<a href="/Documentation/Screenshots/Phone%20Notification%20Bolus%20Failure.png"><img src="/Documentation/Screenshots/Phone%20Notification%20Bolus%20Failure.png?raw=true" alt="Screenshot of bolus failure notification" width="170"></a>

<a href="/Documentation/Screenshots/Watch%20Complication.png"><img src="/Documentation/Screenshots/Watch%20Complication.png?raw=true" alt="Screenshot of glucose complication on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Carb%20Entry.png"><img src="/Documentation/Screenshots/Watch%20Carb%20Entry.png?raw=true" alt="Screenshot of carb entry on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Bolus.png"><img src="/Documentation/Screenshots/Watch%20Bolus.png?raw=true" alt="Screenshot of bolus entry on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Menu.png"><img src="/Documentation/Screenshots/Watch%20Menu.png?raw=true" alt="Screenshot of the app menu on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Notification%20Reservoir.png"><img src="/Documentation/Screenshots/Watch%20Notification%20Reservoir.png?raw=true" alt="Screenshot of bolus failure notification on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Notification%20Bolus%20Failure.png"><img src="/Documentation/Screenshots/Watch%20Notification%20Bolus%20Failure.png?raw=true" alt="Screenshot of bolus failure notification on Apple Watch" width="141"></a>

# Documentation

Please visit the [Loop Docs](https://loopkit.github.io/loopdocs/) for installation, algorithm, and other details.

For FAQs and other tips, refer to the [Wiki](https://github.com/LoopKit/Loop/wiki)

(Note: there is also a tab for the Wiki at the top of this page)

# License and Code of Conduct

Please read the [LICENSE](/LICENSE.md) and [CODE_OF_CONDUCT](/CODE_OF_CONDUCT.md)
