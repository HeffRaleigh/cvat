## Google Analytics for CVAT

### Description

This application allows you to integrate Google Analytics with CVAT

### Configuring

  * Set up a Google Analytics (GA) account and create a GA New Property for CVAT
  * Copy the Tracking ID for the new property
  * Navigate to `/cvat/cvat/apps/google/static/google/js` and use something like `vi` to edit the `enginePlugin.js` file
  * 
  * Save the task.
  * Annotate the task.
  * Save your work and task performance data will automatically be sent to CloudFactory's Workstream platform.
