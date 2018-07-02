# :iphone: BlueRain < Name > App

Description of app

————— TODO: Add Screenshot here —————

## Compatibility

| 🌏 Web | 🖥 Electron | 📱 React Native |
| :---: | :--------: | :------------: |
| :heavy_check_mark:  | :heavy_check_mark: | :heavy_multiplication_x: |

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

### Component One

< Description of component >

#### **Props**

- `path`

  | Label       | Value                                                        |
  | ----------- | ------------------------------------------------------------ |
  | Type        | String                                                       |
  | Required    | ✅                                                            |
  | Description | < description ... > |

- `name`

  | Label       | Value                                                        |
  | ----------- | ------------------------------------------------------------ |
  | Type        | String                                                       |
  | Required    | ✘                                                          |
  | Description | < description ... > |

## Localization Support

< list supported languages >

## RTL

< RTL Support >
