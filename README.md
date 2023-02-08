# 🪐 AdminMe

> A dashboard for all of your administration needs.

## [Live Demo on Netlify](https://adminme.netlify.app/)
[![Netlify Status](https://api.netlify.com/api/v1/badges/3a62c955-4da0-4f05-aaf0-c7a824096e9e/deploy-status)](https://app.netlify.com/sites/adminme/deploys)

<img src="https://github.com/alexisintech/adminme/blob/main/public/assets/dashboard.jpg" width="100%" />

<!-- FEATURES -->
## ⭐ Features

### Global
- Light and dark mode for accessibility
- Collapsible side bar for increasing view width
- Search bar (non-functional)

### Dashboard
- Metrics, analytics, charts, and other data all viewable in one place (mock data was used)

### Data
- Manage Team, Contacts Information, and Invoice Balances use Data Grid to display mock data

### Pages
- Profile Form uses Formik and Yup (submitting the button will console log the form data)
- Calendar has a fully interactive and functional calendar using FullCalendar (refreshing the page will lose any data entered)
- FAQ Page uses the Accordion component provided by MUI

### Charts
- Bar, Pie, Line, and Geography charts were modified using Nivo documentation (mock data was used)

<!-- BUILT WITH -->

## 🛠️ Built With

- React.js, React Router, React Pro Sidebar
- Vite, Node.js
- MUI Data Grid
- FullCalendar
- Formik, Yup
- Nivo
- HTML5/CSS3, Javascript ES6
- ESbuild, ESlint, Stylelint
- VSCode

<!-- GET YOUR OWN COPY -->

## 🚀 Get your own copy running!
1. Navigate to the folder you would like to store the project
2. Clone the repo
   ```sh
   git clone https://github.com/alexisintech/adminme.git
   ```
3. Switch into the directory that was just created
    ```sh
    cd adminme
    ```
4. Install NPM packages
   ```sh
   npm install
   ```
5. To run the application, use `npm run start` to run the app in a development environment

*The page will reload if you make edits.*<br />

<!-- ROADMAP -->

## 🌠 Roadmap

- [X] Utilize Material UI for consistent, reusable components
- [X] Light/Dark mode for accessibility
- [ ] Mobile-first responsiveness

See the [open issues](https://github.com/alexisintech/adminme/issues) for a full list of proposed features (and known issues).

<!-- TEA SPILL -->

## 🌝 Tea Spill
This project was one of the best learning experiences I have had so far; especially when it comes to building with React. Here are some of the things I learned:
- Tailwind Shades will take a color that you have (say you have a hex code) and it will create an array of shades for that color. In this project, Tailwind Shades was used to create the MUI theme of the application.
- Increased MUI skills
  - Explored how to create a custom theme globally to use throughout the app.
  - Learned how to pass a mode to the theme so that light and dark mode can be triggered (used the useContext hook for setting up the light/dark mode logic so that it can be accessed anywhere in the app)
  - useMediaQuery for writing styling logic in components
 - Data Grid provides easily customizable tables with a VAST amount of functionality
 - FullCalendar... wow. The documentation is amazing, and now that I know this tool exists, I'm so excited to use it in future projects.
 - Nivo charts - the documentation is insane!! You can customize the charts right in the documentation and copy and paste the code into your project. Extremely customizable, easily built charts.
 - Formik + Yup have definitely swayed me away from React Hook Form. The documentation seems more palatable for me, and these tools were easier to use in general.
