CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Installation
 * Credits


INTRODUCTION
------------

This module provides the Archive.Org handler for Video Embed Field.

Users will be able to add Archive videos to their site (both traditionally on the node itself, and in Views) simply by copying the standard URL. No hassle with expecting a user to understand what piece of the embed code to copy specifically. There are no teaser images for thumbnails, the thumbnail/preview image is handled at Archive.org. 

Height and width are also adjustable in settings, while there is a default of 640x480.


REQUIREMENTS
------------

- Video Embed Field
  https://drupal.org/project/video_embed_field
- Chaos Tools
- Drupal 7 environment with Image, File, Field, and Field SQL storage enabled


INSTALLATION & USE
------------
1. Place the module folder and its files at the traditional area for modules. It is not necessary to have this module within the Video Embed Field module folder, and can be picked up easily when placed in the normal module folder.
2. Enable the module as usual (Video Embed Archive.org).
3. Navigate to “admin/config/media/vef_video_styles”, configure the default size for the video in Normal and Teaser settings.
4. Add you video field per Video Embed Field, and enable Video Embed Archive.org videos to use the field in the field settings.
5. Copy the default URL (example: https://archive.org/details/[VIDEONAME]) and paste into the field.


CREDITS
------------
* Danielle Wilcox, State of Arizona (Casist)