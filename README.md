# Node-Red-4-farmOS

Node Red Custom nodes for interacting with farmOS API. <br />
Install by running **npm i @farmer-ed/node-red-4-farmos**  from **.Node Red** directory.

https://youtube.com/playlist?list=PLV_VqXF2pXXJdFjVhzdzDKskzkeXqLd8f

## farmOS Oauth2:

**Inputs:** <br />
msg.payload.url <br />
msg.payload.username <br />
msg.payload.password <br />
msg.payload.client_id <br />
msg.payload.client_secret <br />
msg.payload.scope <br />

**Outputs** <br />
msg.payload <br />
msg.bearer <br />
msg.error <br />

**Global Variables** <br />
farmOSurl <br />
token <br />

## farmOS API:

**Inputs:** <br />
msg.payload

**Outputs** <br />
msg.payload
