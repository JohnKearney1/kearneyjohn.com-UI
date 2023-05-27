# kearneyjohn.com-UI

This is one of two repositories created for my portfolio website, [kearneyjohn.com](https://kearneyjohn.com/). If you are looking for the 2D Windows themed OS repository you can find it [here](https://github.com/JohnKearney1/kearneyjohn.com-OS).

![3D UI](./img/UI.gif)

# About

This repository is the host component for the guts of the portfolio website. It's a React + Typescript website that renders a loading screen and a monitor screen and allows the user to manipulate the environment, zoom in to the computer monitor, and use it. The monitor screen is an iFrame that points to the OS website, but you can easily change which website is rendered onscreen. 

To setup a dev environment:
```bash
# Clone the repository

# Install dependencies 
npm i

# Run the local dev server
npm run dev
```

To serve a production build:

```bash
# Install dependencies if not already done
npi i

# Build for production
npm run build

# Serve the build using express
npm start
```

Change the iFrame in `src/Application/World/MonitorScreen.ts (ln ~187)` to point to your website of choice.