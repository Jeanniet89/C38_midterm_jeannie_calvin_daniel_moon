# Got Tech?
[![Contributors][contributors-shield]][contributors-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- TABLE OF CONTENTS -->
## Table of Contents

- [About the Project](#about-the-project)
  - [Built With](#built-with)
  - [Used Packages & Modules](#used-packages-&-modules)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Contributing](#contributing)
- [Contact](#contact)
- [API](#api)
  - [API Params](#api-params)

<!-- ABOUT THE PROJECT -->
# Got Tech? Midterm Project

[Got Tech?](https://got-tech-app.herokuapp.com/ )

This is a Job Search engine focusing on SoftWare Development.

## Built With

- [Bootstrap](https://getbootstrap.com)
- [React](https://react.com)

## Used Packages & Modules

- [Axios](https://www.npmjs.com/package/react-axios)
- [Yarn](https://www.npmjs.com/package/yarn)
- [Heroku](https://www.heroku.com/)
- [Express](https://www.npmjs.com/package/express)
- [React Router DOM](https://www.npmjs.com/package/react-router-dom)

## Prerequisites

- npm
  `sh npm install npm@latest -g `

## Installation

1. `git clone` this repo
   `sh git clone https://github.com/your_username_/Project-Name.git `
2. `cd` into it.
3. `Install` NPM packages
   `sh yarn install `
4. `cd client && yarn install`
5. `cp .env.sample .env`

## Available build commands

- `yarn dev`: Runs BOTH your Express.JS and React developer environment locally at the same time. Any logs coming from Express will be prefaced with `[0]`, any logs from `create-react-app` will be prefaced with `[1]`.
- `yarn server`: Runs JUST your Express.JS server.
- `yarn client`: Runs JUST your front-end React app.

Open [http://localhost:3000](http://localhost:3000) to view your local React app in the browser. The page will reload if you make edits.

## To deploy

NOTE: Heroku specifically runs `npm start`, so don't remove that from your package.json file.

- `heroku create your-app-name`
- `heroku config:set MONGODB_URL=<insertYourAtlasDbUri>`
- `git push heroku master`

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create.
Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- CONTACT -->
## Contact

- Jeannie Torres - jeanniet89@gmail.com
- [Moon Guo--Front/Backend](https://github.com/DevloperM)
- [Calvin Malagon--Front/Backend](https://github.com/Cal9233)
- [Daniel Riera--Front/Backend](https://github.com/DanRie19)

Project Link: [https://github.com/wyncode/C38_midterm_jeannie_calvin_daniel_moon](https://github.com/wyncode/C38_midterm_jeannie_calvin_daniel_moon)

## API
https://jobs.github.com/api

### API Params
description — A search term, such as "ruby" or "java". This parameter is aliased to search.
location — A city name, zip code, or other location search term.
lat — A specific latitude. If used, you must also send long and must not send location.
long — A specific longitude. If used, you must also send lat and must not send location.
full_time — If you want to limit results to full time positions set this parameter to 'true'.

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/wyncode/C38_midterm_jeannie_calvin_daniel_moon.svg?style=flat-square
[contributors-url]: https://github.com/wyncode/C38_midterm_jeannie_calvin_daniel_moon/graphs/contributors
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/jeannie-torres-6628bb96/

