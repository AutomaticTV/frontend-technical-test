
# frontend-technical-test

Mediapro is looking for a talented frontend developer to carry out a simple but effective task to list the teams of an organization, you will find this list through the next url 
```https://api.npoint.io/b7169ab627bfe9d850bd```

Your task will be to create a webapp in React that complies with the design shown in design.pdf and in addition, this list must meet the following requirements:

- It must be ordered alphabetically by the location of the team
- The first column must be the team's logo. In the endpoint's response you will find a key named "logo":
    - If the logo type is "attach" you will find the correspoding image in the folder assets/images that will match with the key "data"
    - If the logo type is "string" you will need to render the correspoding image located in the key "data"
    - If there is not logo, you will have to render a defult image located in assets/image folder named "default.png"
- In the case that a team does not have "nextSchedule", the table should display "N/A"
- The "State" column must be a distinct label as follows:
    - recording -> green
    - recorded -> blue
    - offline -> red
    - default / undefined / null -> gray with text "N/A"
- The "Preview" column will be a section of actions, where we will have the following conditions:
    - If there is not active session (recording or recorded) we must ensure the modal does not open because there are not video to show.
        - Open eye icon -> green, clickable that should open a modal with a preview of the video video_example.mp4 and have a title with the name of the team
        - Closed eye icon -> red, NOT clickable

## What we value

- Typescript
- Responsive design
- Clean code

## Extra Points

- Paginate the table with 10 elements per view
- Loader animations even if it does not have to wait