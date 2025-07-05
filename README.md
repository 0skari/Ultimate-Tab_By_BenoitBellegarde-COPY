# ***THIS IS A COPY OF THE ULTIMATE-TAB REPOSITORY (as of 31.1.2025) BY [Benoit Bellegarde](https://github.com/BenoitBellegarde/). THE [ORIGINAL GITHUB REPO](https://github.com/BenoitBellegarde/UltimateTab) HAS BEEN TAKEN DOWN (presumably due to scraping issues with ultimate-guitar.com). I DO NOT OWN THE CODE IN THIS REPOSITORY, AND I DO NOT GIVE ANYONE CONSENT TO DOWNLOAD OR USE THE CODE. ANY ACTIVITY, INCLUDING USAGE, RUNNING, OR DOWNLOADING OF THE CODE IN THIS REPOSITORY, IS AT YOUR OWN RISK.***

Please do not get me or yourself into trouble. If Mr. Bellegarde has any objections to me republishing this repository, please contact me directly or open a new [issue](https://github.com/0skari/Ultimate-Tab_By_BenoitBellegarde-COPY/issues). If Ultimate Guitar has any objections to me republishing this repository, I, in fact, probably won't give a fuck. I hope the original Ultimate-Tab site will be up and running again soon. The original repo operates under the [MIT License](https://opensource.org/licenses/MIT).



⚠️ **This mirror repository was published on _July 5, 2025_, and the status of the original Ultimate-Tab project may still change. Please check the status of the [original repository](https://github.com/BenoitBellegarde/UltimateTab) or any new announcements from the original author before taking any action.**

# ------------------------------------------



# Ultimate Tab - Ads-free Ultimate Guitar tabs

> [!NOTE]
> Update 2024/08/07 : The project is once again accessible via the URL: https://ultimate-tab.com 🎉
**<-SITE DOWN**


**Link** : [https://ultimate-tab.com](https://ultimate-tab.com) **<-SITE DOWN**

A web application that delivers an enhanced, ads-free and fast responsive interface to browse guitar tabs scraped from Ultimate Guitar.

![Ultimate Tab Screenshot](https://i.ibb.co/RYLXkNc/586shots-so.png)
![Ultimate Tab Screenshot](https://i.ibb.co/THdSmPK/673shots-so.png)

## Features

- Browse responsive guitar tabs scraped in real time from Ultimate Guitar.
- Chords visualizer with official diagrams from Ultimate Guitar.
- Chords transposer.
- Autoscroll tab.
- Font size management
- Backing track player (using YouTube API).
- Add tabs to favorites without the need for an account (stored in local storage).

## Features in Development

- Export tab as PDF.

## Technologies

Ultimate Tab has been built with a modern stack, including:

- [NextJS](https://nextjs.org/) - React Framework
- [Puppeteer](https://pptr.dev/) - Headless browser used for web scraping
- [React Query](https://tanstack.com/query/v3/) - Server state management
- [React Context API](https://react.dev/reference/react#context-hooks) - Client state management
- [ChakraUI](https://chakra-ui.com/) - UI Component Library
- [Vexchords](https://github.com/0xfe/vexchords) - Chords renderer library

## Installation

To run Ultimate Tab locally, you must have Node.js and NPM or Yarn installed on your computer. Follow these steps to get started:

1. Clone this repository using `git clone https://github.com/BenoitBellegarde/UltimateTab.git` **<-REPO DOES NOT EXIST**
2. Navigate to the project directory using the terminal or command prompt.
3. Run `npm install` or `yarn install` to install the dependencies.
4. Run `npm run dev` or `yarn dev` to start the development server.
5. Create `.env.local` file and add a variable `YOUTUBE_API_KEY` with a YouTube API key as value to get backing tracks
6. Open http://localhost:3000 in your web browser to see Ultimate Tab running.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any features or bug fixes.

## License

Ultimate Tab is licensed under the [MIT License](https://opensource.org/licenses/MIT).
