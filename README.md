
# frontend-technical-test

Mediapro is looking for a talented frontend developer to carry out a simple but effective task to list the teams of an organization, you will find this list in the file teams.json.

Your task will be to create a webapp in React that complies with the design shown in design.pdf and in addition, this list must meet the following requirements:

- It must be ordered alphabetically by the location of the team
- The first column must be the team's logo that you will find in the assets folder. In the case that the icon path does not arrive, we must use a default image that will be in assets/default.png
- In the case that a team does not have "nextSchedule", the table should display "N/A"
- The "State" column must be a distinct label as follows:
    - recording -> green
    - recorded -> blue
    - offline -> red
    - default / undefined / null -> gray with text "N/A"
- The "Preview" column will be a section of actions, where we will have the following conditions:
    - Open eye icon -> green, clickable that should open a modal with a preview of the video video_example.mp4 and have a title with the name of the team
    - Closed eye icon -> red, NOT clickable

## Notes

If there is not active session (recording or recorded) we must ensure the modal does not open because there are not video to show.

## What we value

- Typescript
- Responsive design

## Extra Points

- Paginate the table with 10 elements per view
- Loader animations even if it does not have to wait