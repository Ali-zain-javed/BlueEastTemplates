# BlueRain < Name > App

Description of app

————— TODO: Add Screenshot here —————

## Compatibility

| 🌏 Web | 🖥 Electron | 📱 React Native |
| :---: | :--------: | :------------: |
|   ✅   |     ✅      |       ✅        |

## Installation

Run the following command in the plugin directoy:

```shell
yarn add @blueeast/bluerain-app-name
```

Then in your boot function, pass the plugin like this:

```javascript
import BR from '@blueeast/bluerain-os';
import AppName from '@blueeast/bluerain-app-name';

BR.boot({
 apps: [AppName]
})
```

## Info

| Property | Value    |
| -------- | -------- |
| appName  | XYZ |
| slug     | x-y-z |

## Hooks

This app provide the following hooks to dynamically modify it's behavior:

### hook one

< Description >

#### **Parameters**

| Name  | Type                          | Description                                                  |
| ----- | ----------------------------- | ------------------------------------------------------------ |

#### **Returns**

| Name  | Type                          | Description                                                  |
| ----- | ----------------------------- | ------------------------------------------------------------ |

## Components

In addition to hooks, the app also registers various components that work as building blocks to generate the layout.

### SettingsLayout

This is the main layout component and is the top level visible view of the app. This layout can also be reused to create setting sections in other apps and plugins.

#### **Props**

- `path`

  | Label       | Value                                                        |
  | ----------- | ------------------------------------------------------------ |
  | Type        | String                                                       |
  | Required    | ✅                                                            |
  | Description | This is the path of the page where this layout is used. It is used to build sub pages/routes for each settings item. |