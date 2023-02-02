# create-tabs

1. The [`index.js`](./index.js) file organizes multiple files so I have less in my routes file.
2. The [`instructorNav.js`](./InstructorNav.js) file is what my users see on the screen.
3. The [`TabNavItem.js`](./TabNavItem.js) file sets the clicked tab to "active" so that is the tab showing on my instructorNav screen.
4. The [`TabContent.js`](./TabContent.js) filechecks if the id is active and "tells" react what content to display using the `<div className>` of the correct component.