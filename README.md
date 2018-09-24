Australian Government Design System Starter Pack
==========================

> Get up and running with examples of the design system's components in action and some great `npm` scripts


## Contents

* [Install](#install)
* [Contributing](#contributing)
* [License](#license)


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Install

Download, clone, or fork this repository and run `npm install` to install all dependencies.

After you have all dependencies installed, run `npm run watch` to spin up a new local server and watch for changes on `*.scss` files. Changes will be injected into your browser so you don’t even need to refresh thanks to [Browser Sync](https://www.browsersync.io/).



**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Docs folder

The `docs` folder in the root directory contains all the assets required to deploy the Ui-Kit starter page to web. The `index.html` file references the `main.css` file and `script.min.js` assets to generate the page. We are using a folder called `docs` to hold these assets, since it is the default folder name for using [github pages](https://pages.github.com/). 

The current Ui-Kit starter is published at [https://govau.github.io/uikit-starter/](https://govau.github.io/uikit-starter/)

The `script.min.js` and `_uikit.scss` are generated by [pancake](https://github.com/govau/pancake). Pancake ensures that all of the relevant SASS files for the components you have downloaded are imported into the `_uikit.scss` file. It does this for the javascript files into the `script.min.js` file.


The `main.scss` file includes and import of `_uikit.scss` along with any customisations that may have been made. We use [node-sass]("https://www.npmjs.com/package/node-sass?activeTab=versions") to convert the `src/sass/main.scss` file into a `main.css` file in the `docs/css` directory. The [autoprefixer]("https://www.npmjs.com/package/autoprefixer") is then used to add vendor prefixes to this `main.css` file for browser compatibility. Refer to the package.json file for how we've set this up. 


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Contributing

To contribute to the Australian Government Design System Starter Pack:
1. Fork the project & clone it locally.
1. Create a new branch for the work that is going to be completed.
1. Complete the work and test it to the best of your abilities following the [guidelines here](https://github.com/govau/uikit#checklist-and-browser-support).
1. Once the work is completed, write a good commit message.
1. Push your work to GitHub and create a new pull request.
1. Respond to any code review feedback.

**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## License

Copyright (c) Commonwealth of Australia. With the exception of the Commonwealth Coat of Arms and where otherwise noted, this work is licensed under the [MIT license](https://raw.githubusercontent.com/govau/uikit-starter/master/LICENSE).


**[⬆ back to top](#contents)**

# };
