# react-basic-search-page
Technical interview problem/question.

For this task, create a search page with a layout similar to what is shown in the following image
![Alt text](/task/page-layout.png?raw=true "Search page layout")

## Breakdown
Your page will have 3 major components namely, the search bar, the listing and the filters. You can use your creativity to arrange the layout however you like but make sure to keep these in your layout. 

Use the following JSON to populate your list
```yaml
[
   {
      "id":1,
      "caseTitle":"Khallid Hussain, etc v. Nazir Ahmad, etc",
      "caseAuthor":"Mr. Justice Yahya Afridi"
   },
   {
      "id":2,
      "caseTitle":"The State through Director ANF, Peshawar v. Aurangzeb",
      "caseAuthor":"Mr. Justice Qazi Muhammad Amin Ahmed"
   },
   {
      "id":3,
      "caseTitle":"State through Advocate General, K.P. Peshawar v. Sabz Ali Khan and another",
      "caseAuthor":"Mr. Justice Qazi Muhammad Amin Ahmed"
   },
   {
      "id":4,
      "caseTitle":"Province of Punjab, etc v. Hafiz Muhammad Ahmad",
      "caseAuthor":"Mr. Justice Syed Mansoor Ali Shah"
   },
   {
      "id":5,
      "caseTitle":"Mst. Rukhsana v. Rehmanullah and another",
      "caseAuthor":"Mr. Justice Qazi Muhammad Amin Ahmed"
   },
   {
      "id":6,
      "caseTitle":"Mst. Naseem v. Farhad Khan & another",
      "caseAuthor":"Mr. Justice Qazi Muhammad Amin Ahmed"
   },
   {
      "id":7,
      "caseTitle":"Haji Muhammad Latif v. Muhammad Sharif, etc",
      "caseAuthor":"Mr. Justice Sajjad Ali Shah"
   },
   {
      "id":8,
      "caseTitle":"Zia Ullah and Waheed Anwar v. The State",
      "caseAuthor":"Mr. Justice Ijaz Ul Ahsan"
   }
]
```

- The user should be able to use the search bar to search through both the case title and the case author.
- There should also be an option to sort the list by either of these columns.
- The filters list the names of the judge appearing in the above JSON, extract the unique authors and create a filter to choose either one of multiple judges.




# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

