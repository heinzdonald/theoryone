= Resource Conflict =

== Requirements ==

References and nodereference module: http://drupal.org/project/references
Date API module: http://drupal.org/project/date

== How does Resource Conflict work? ==

Resource Conflict requires two things to be set up within a content type.  The
content type must have at least one nodereference field and at least one
Date API field.  The resource conflict option must be enabled, and at least
one nodereference field must be selected and at least one date field must be 
selected. These will be the resources which will be checked for conflicts.

If there is a pre-existing event which conflicts in both time and resource, a
form error is set and the user is forced to either book a different resource or
change the event dates/times.

Project Page: http://drupal.org/project/resource_conflict