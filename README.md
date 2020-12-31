Video Embed Archive.org
-----

This module provides an additional handler for Video Embed Field by allowing Archive.org videos to be integrated.

It is user-friendly in that it does not require the embed code, and automatically translates the default video URL for the end user into the typical embed code provided by the Archive site. Due to the integration for Video Embed Field, these videos will be able to be used in Views as well.

This is a basic handler where the site administrator is able to set default widths of these videos in the settings page - Archive.org will handle the rest using their embed video settings.

Requirements
----

- Video Embed Field
  https://github.com/backdrop-contrib/video_embed_field
- Backdrop environment with Image, File, Field, and Field SQL storage enabled

Notes
----

*The thubmbnail is currently set to a default because there were issues getting the thumbnails to load from Archive.org. I will file an issue in the issue queue about this.

Project Information
----

This is a port from https://www.drupal.org/project/video_embed_archive
Original Drupal 7 module maintainers: jeremylichtman, Casist

Ported to Backdrop by Kristin at Palante Technology Cooperative
Looking for co-maintainers
