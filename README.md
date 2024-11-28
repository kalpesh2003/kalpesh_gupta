**first run
npm insall**


**after that try to run**
**npm run dev**

**if the error occur like this:PS E:\portfolio\project_3D_developer_portfolio> npm install**
npm error code ERESOLVE
npm error ERESOLVE could not resolve
npm error
npm error While resolving: react-tilt@0.1.4
npm error Found: react@18.2.0
npm error node_modules/react
npm error   react@"^18.2.0" from the root project
npm error   peer react@"^16.8.0 || ^17.0.0 || ^18.0.0" from @react-spring/animated@9.6.1
npm error   node_modules/@react-spring/animated
npm error     @react-spring/animated@"~9.6.1" from @react-spring/core@9.6.1
npm error     node_modules/@react-spring/core
npm error       @react-spring/core@"~9.6.1" from @react-spring/three@9.6.1
npm error       node_modules/@react-spring/three
npm error         @react-spring/three@"~9.6.1" from @react-three/drei@9.56.27
npm error         node_modules/@react-three/drei
npm error     @react-spring/animated@"~9.6.1" from @react-spring/three@9.6.1
npm error     node_modules/@react-spring/three
npm error       @react-spring/three@"~9.6.1" from @react-three/drei@9.56.27
npm error       node_modules/@react-three/drei
npm error         @react-three/drei@"^9.56.24" from the root project
npm error   17 more (@react-spring/core, @react-spring/shared, ...)
npm error
npm error Could not resolve dependency:
npm error peer react@"^15.0.0 || ^16.0.0-beta || ^16.0.0" from react-tilt@0.1.4




**Run This Command**
**npm uninstall react-tilt
npm install react-parallax-tilt**


After that run this command
**npm install vite react react-dom**

after that try to run 
**npm run dev**


if thihs typr of error occoured:
plugin:vite:import-analysis] Failed to resolve import "react-tilt" from "src\components\Works.jsx". Does the file exist?
E:/portfolio/project_3D_developer_portfolio/src/components/Works.jsx:2:17
15 |  }
16 |  import React from "react";
17 |  import Tilt from "react-tilt";
   |                    ^
18 |  import { motion } from "framer-motion";
19 |  import { styles } from "../styles";
    at formatError 


Run this command onby one

**npm uninstall react-tilt**

**npm install react-parallax-tilt**


****this do it compulsary if you not project will gives error**

**Update Import in Works.jsx: Replace:**

**jsx
Copy code
**import Tilt from "react-tilt";**
**With**:

**jsx**
**Copy code**
**import Tilt from "react-parallax-tilt";**


extra error
Like this:
if browser error occoured on version
Browserslist: caniuse-lite is outdated. Please run:
  npx update-browserslist-db@latest
  Why you should do it regularly: https://github.com/browserslist/update-db#readme



run this commandd:
**npx update-browserslist-db@latest**


and finally run npm run dev



