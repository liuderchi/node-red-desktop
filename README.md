# Node-RED Desktop

This is a desktop applicaiton of Node-RED

![screen](https://raw.githubusercontent.com/sakazuki/node-red-desktop/doc/screenshot.png)

## Benefit: Quick and Easy

You can 
- easily setup Node-RED on your desktop.
- quickly create and discard a flow many times.
- easily integrate with cloud services with the public HTTP endpoint.
  - twilio, alexa, google home etc...

And also,

You can use almost all powerful and useful Node-RED features
  - install nodes from the [public Library](https://flows.nodered.org/) or else.
  - [projects](https://nodered.org/docs/user-guide/projects/)
  - etc.

## Node-RED-Desktop features

- [Node-RED](https://nodered.org/) v0.20.5
- [ngrok](https://ngrok.com/) integrated 
- multi language
  - english
  - japanese
- auto updater

## How to install Node-RED-Desktop

1. Download the installer from [release page](https://github.com/sakazuki/node-red-desktop/releases).
1. Run the installer.

## How to use Node-RED

1. the same way as Node-RED usage
1. If you are a newbee, see [Node-RED document](https://nodered.org/docs/).

## How to publish the HTTP endpoint

1. create a flow using "http in" and "http response" nodes.
1. click [Endpoint]-[ngrok Connect]
1. you will get the domain such as https://1234xxxx.ngrok.com.
1. access to the above public url.

## How to enable Node-RED projects feature

1. go [File]-[Settings...]
1. checked [Projects enabled]
1. click [Restart to apply]


## How to build

  ```
  git clone https://github.com/sakazuki/node-red-desktop.git
  cd node-red-desktop
  npm install
  npm run build
  ```

