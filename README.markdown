# TouchNotifications

## Overview

TouchNotifications is an API that provides a single coherent interface for displaying user notifications.

## TODO

* Replace all drawing code with UIBezierPath.
* Use CoreAnimation CATransitions instead of the UIView based animations.
* Don't using any private knowledge of window/view structure
* Hook up with iOS 4.0 local notifications.
* Create UIViewController category for ease of use
* Create "NOW" notifications that jump to front of the queue.
* Break out concept of queue based notifications from now notifications.
* Implement other styles of notifications (perhaps:)
** Twitterfic style "letter" notifications (used when posting to instapaper)
** Reeder style status bar notifications


## Requirements

TouchUI. For the demo project(s) to work you need to download TouchUI and place it in the same parent directory as TouchNotifications.
