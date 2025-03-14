---
difficulty: easy
category: osint
---

# Nightmare Fuel

NYPD investigated an abandoned building in Brownsville after reports of suspicious activity and missing persons. Body cam footage from the investigation showed unusual characteristics. Your task is to analyze the provided video file to find a hidden password.

## Background

Following multiple reports of suspicious activity and concerns about missing persons, the NYPD conducted an investigation of an abandoned building in Brownsville, Brooklyn. Responding officers were equipped with body-worn cameras to document their findings. The footage recovered from the body cams revealed several unusual characteristics, raising further questions about the events within the building.

## Objective

Analyze the provided video file to extract the hidden password from its metadata.

## Resources

- Video File: [Download Link](link_to_video_file.mp4)

## Hints

1. Have you tried examining the file's properties?
2. Sometimes, the information you seek isn't *in* the video, but *about* the video.
3. Metadata can be viewed with various tools, including built-in operating system features and dedicated metadata viewers.

## Solution

1. **Download the Video File:** Download the provided video file (`link_to_video_file.mp4`) to your local machine.
2. **Examine File Metadata:** Use a tool capable of viewing file metadata. This could be:
   - **Windows:** Right-click the file, select "Properties," and then the "Details" tab.
   - **macOS:** Right-click the file, select "Get Info."
   - **Linux:** Use a command-line tool like `exiftool` (e.g., `exiftool video_file.mp4`).
   - **Online Metadata Viewer:** Upload the file to a reputable online metadata viewer.
3. **Extract the Password:** Locate the password within the metadata fields. It may be in a field like "Comments," "Description," "Author," or a custom field. The password is: `fh453n3fk45b384gm$&%#fjksdfmo94853ff`

## Flag

OSINT{fh453n3fk45b384gm$&%#fjksdfmo94853ff}

## Notes

This challenge focuses on metadata analysis, a crucial OSINT skill. The narrative provides context while keeping the technical objective clear and achievable.
