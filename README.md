VisualTweak is a powerful mobile application for editing and manipulating images with ease. With VisualTweak, users can effortlessly capture new images using their phone's camera or import images from their gallery. The app offers a wide range of advanced editing features, including the ability to change backgrounds, crop images, resize, and add additional elements such as text or other images.

# Getting Started

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

### Project Structure
AwesomeProject
  -src
    |--- assets
    |      |--- fonts
    |            |--- <<Your Fonts>>
    |      |--- images
    |            |--- << Your Images>>
    |
    |
    |--- route
    |      |--- screenName
    |      |      |--- index.js
    |      |      |--- styles.ts
    |      |      |--- helper.ts
    |      |      |--- screenName.tsx
    |      |      |--- screenName.test.tsx
    |      |      |--- useAnimated.ts (Optional)
    |      |      |--- components (Optional)
    |      |
    |      |--- screenName2
    |              |--- index.js
    |              |--- styles.ts
    |              |--- helper.ts
    |              |--- screenName.tsx
    |              |--- screenName.test.tsx
    |              |--- useAnimated.ts (Optional)
    |              |--- components (Optional)
    |  
    |--- navigation
    |      |--- NavigationContainer
    |      |--- Route
    |      |--- NavigationService
    |      |--- linking
    |
    |--- networking
    |      |--- apiclient
    |      |--- requestInterceptor (Assuming axios)
    |      |--- responseInterceptor (Assuming axios)
    |      |--- urls
    |      |--- UserApi (You can create a file for a group of related api calls)
    |
    |--- components
    |      |---Button (This is will have same structure as the screen)
    |      |      |--- index.ts
    |      |      |--- Button.tsx
    |      |      |--- styles.ts
    |      |      |--- helper.ts
    |      |      |--- useAnimated.ts (Optional)
    |      |
    |      |--- <<Any other component>>
    |
    |--- hooks
    |      |--- useBackHandler.ts
    |      |--- useKeyboard.ts
    |      |--- useUploadImage.ts
    |      |--- useCamera.ts
    |      |--- <<Any other hook>>
    |
    |--- types 
    |      |--- UserInterface
    |      |--- MediaInterface
    |      |--- AppConfigInterface
    |
    |--- redux
    |      |--- store.ts
    |      |--- slices
    |            |--- UserSlice
    |            |--- IntermittentSlice
    |            |--- ToastSlice
    |
    |--- utils
    |      |--- Analytics.ts
    |      |--- CommonUtils.ts
    |      |--- Logger.ts
    |      |--- ErrorManager.ts
    |      |--- DateTimeUtils.ts
    |      |--- EncryptedStore.ts
    |      |--- string.ts
    |      |--- constants.ts
    |      |--- enums.ts


# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
