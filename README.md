# mp4-volume-booster-updates
# MP4 Volume Booster – Update Metadata

This repository hosts the update information for the **MP4 Volume Booster** desktop application.

The application checks for updates by reading the JSON file:

This JSON file contains:

- The latest available version number  
- The download link for the new release  
- Release notes describing improvements and changes

Example:

```json
{
  "version": "1.1.0",
  "download_url": "https://github.com/SingnShine/mp4-volume-booster-updates/releases/latest",
  "notes": "Includes FFmpeg updates and audio improvements."
}
