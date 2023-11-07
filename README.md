# Home Assistant Node-Flows
Collection of usable Flows and Subflows in Node-RED for usage with Home Assistant

## How to use it

- You need to install following npm packages:
```
"node-red-contrib-eztimer": "1.2.7",
"node-red-contrib-flow-manager": "0.7.4",
"node-red-contrib-home-assistant-websocket": "0.57.4",
"node-red-contrib-moment": "5.0.0",
"node-red-contrib-msg-speed": "2.1.0",
"node-red-contrib-stoptimer": "0.0.7",
"node-red-contrib-time-range-switch": "1.2.0",
```
- Create `node-red/flow-manager-cfg.json` and set `fileFormat` to `yaml` (see [docs](https://flows.nodered.org/node/node-red-contrib-flow-manager))
- Put flows into `node-red/flows` and subflows into `node-red/subflows` directory
- Restart Node-RED
- Create missing config nodes
