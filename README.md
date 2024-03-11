# CPSC6175 Assignment Two

## Instructions
You will be connecting your React front end to the backend APIs you created. Using the lectures for Spring React you are to create at least one new route for your Nasa Api connections. 

Your new page should use react-router-dom to navigate to a new URL. You should use Outlet to display the information so the Nav is the same throughout the app. The page should display the picture of the day, a selected date, a count of images, and images between certain dates. You will need at least 4 inputs for this. The one for the date, to and from dates, and count.

Make sure to map through responses when it is an array and just display it once when it is not an Array.

## Notes
* React Router is used to switch between each of the four pages with an Outlet.
* The APODViewer component is common to all pages and displays the results organized into columns.
* User can click on the image to view full size in a new tab.
* API key is set in application.properties if necessary, otherwise using DEMO_KEY

### Screenshots

Current Photo (default landing page)

![fzf6DYo](https://github.com/Pedro-T/nasa-api-6175-assn2/assets/15681739/1906d16b-f8aa-4306-9557-2be0ea94ce3c)


Random Count of Photos

![XcLbSrP](https://github.com/Pedro-T/nasa-api-6175-assn2/assets/15681739/53ff0842-7fa0-4ddc-b53f-c4fcba565f04)


Single Date Selected

![mKyTiiC](https://github.com/Pedro-T/nasa-api-6175-assn2/assets/15681739/a9fb73ab-3ec1-4389-9e4c-200e07f651e5)


Date Range

![BH264AP](https://github.com/Pedro-T/nasa-api-6175-assn2/assets/15681739/2ff0590e-8b93-42f7-a1d7-ab5c34cf35fd)


