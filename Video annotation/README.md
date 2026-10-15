# Video Annotation and Object Tracking

## Project Overview

**Project type:** Video data annotation  
**Task:** Pedestrian detection and tracking  
**Status:** In progress

## Objective

Practice identifying a visible person across selected video frames, assigning a consistent object ID, recording timestamps, and documenting annotation decisions.

## Annotation Guidelines

1. Annotate only objects that are visible in the selected frame.
2. Use the class label `person` for the pedestrian.
3. Assign the tracking ID `P001` to the same person across frames when identity is clear.
4. Record timestamps from the actual video.
5. Use bounding boxes that enclose the visible person as closely as practical.
6. Flag unclear or partially visible objects for review instead of guessing.

## Annotation Fields

- `frame_number`: The frame's position in the video.
- `timestamp`: The time of the frame in the video.
- `object_id`: The consistent ID assigned to the person.
- `class_label`: The object's category.
- `bbox_x`, `bbox_y`: The top-left corner of the bounding box.
- `bbox_width`, `bbox_height`: The box dimensions in pixels.
- `action`: The visible action, such as walking or standing.

## Quality Assurance

I will review timestamps, bounding-box placement, class labels, and tracking ID consistency before considering the annotations complete.

## Project Evidence

- Annotation data: `annotations.csv`
- Annotated frame examples: to be added
- Quality review: to be completed after annotation

## Data Source

To be completed with the video source and applicable usage permissions.

## Project Status

This project is a learning exercise. Results and screenshots will be added after the actual video has been annotated.
