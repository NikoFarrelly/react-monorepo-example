# React/React-native monorepo with Yarn workspaces

You probably found this repo from this [tutorial](https://nickhfarrelly.medium.com/react-react-native-monorepo-with-yarn-workspaces-tutorial-a55e7f4d2d86).

Welcome! This repository is here to serve as an example from the aforementioned tutorial. I hope this is helpful for you.

### Setup (If not following the tutorial)
1. Clone the repo.
2. install all the dependencies
   1. yarn from any folder `yarn`
   2. install pods `cd packages/app/ios && pod install`
   
Now start either the web, or the app.

* Web
   1. `cd packages/web && yarn start`
* App
  1. Start the metro server `cd packages/app && yarn start`
  2. Start an emulated/simulated device, e.g. `yarn ios`
