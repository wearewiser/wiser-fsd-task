# Wiser | Front End Developer Task

## About this task

This task should be completed to be considered for the Front End Developer position at Wiser. The task will test your knowledge of JavaScript (ReactJS), styling and ability to accurately translate design files into code.

## Instructions

Fork this repo. When you have completed the task, push your code and email a link of your fork to <engineering@wearewiser.com> to let us know! The starter code for this task has been generated using [Create React App](https://github.com/facebook/create-react-app).

## The task

Build an image gallery by fetching data from the NASA [Astronomy Picture of the Day](https://api.nasa.gov/) API.

There should be two routes that should display two page components: `Home` and `ImageDetails`.

###Home:

- Display 6 random images from the NASA APOD API, along with their corresponding titles.


![Home](public/home.png)

### ImageDetails:

- Each image displayed on the `Home` page component should be clickable.
- On click of each image, a dynamic route should generated. The route should navigate to the `ImageDetails` page component, which should display the `url`, `title` and `explanation` of the image that was clicked on.
- There should be a back button to return to the home page

![ImageDetails](public/image-details.png)


### Bonus points:

- The `ImageDetails` route path should use the `title` of the image that was clicked. For example in the above design, the path would be `/spiral-galaxy-ngc-1232`, opposed to a generic number ID.
- Sometimes the APOD API returns a video instead of an image. If this happens, the application should display the video thumbnail as an image, instead of the video.
- Add text that reads "Loading images" to the `Home` component. This text should dissapear once the images are displayed.

If you have any questions, please feel free to email <engineering@wearewiser.com>.

### Notes:

- Please ensure this task is built using the ReactJS library.
- Feel free to install any additional packages.
- The app should be responsive for desktop and mobile devices.
- The app should be cross-browser compatible, the latest versions of Safari, Firefox and Chrome is fine.

Good luck! :)
