# Omnichannel Livechat Endpoints

## Agent

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/agent.info/:rid/:token` | Retrieve the current Livechat agent data | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-agent/agent) |
| `livechat/agent.next/:token` |  | [Link](https://github.com/RocketChat/developer-docs/tree/416477aacf3193fe1c499552e2eebe39ad0c1878/api/rest-api/methods/livechat/methods/livechat/inquiries.md#livechat-take-inquiry) |

## Configuration 

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/config` | Get LiveChat widget configuration info and additional visitor data. | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-config) |

## Contacts

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `omnichannel/contact` | Registers a guest user as a new omnichannel contact | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-contact/register-omnichannel-contact) |
| `omnichannel/contact` | Retrieves a contact information | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-contact/omnichannel-fetch-contact) |
| `omnichannel/contact.search` | Search a contact information | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-contact/omnichannel-search-contact) |

## Custom Field

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/custom.field` | Send a custom field | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/custom-fields/send-a-livechat-custom-field) |
| `livechat/custom.fields` | Send an array of custom field | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/custom-fields/send-an-array-of-livechat-custom-fields) |
| `livechat/custom-fields` | Get a list of Livechat custom fields | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/custom-fields/list-livechat-custom-fields) |
| `livechat/custom-fields/:_id` | Get info about a custom field | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/custom-fields/get-info-about-a-custom-field) |

## Message

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/message` | post | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-agent/agent) |
| `livechat/message/:_id` | get  | [Link](https://github.com/RocketChat/developer-docs/tree/416477aacf3193fe1c499552e2eebe39ad0c1878/api/rest-api/methods/livechat/methods/livechat/inquiries.md#livechat-take-inquiry) |
| `livechat/message/:_id` | put | [Link](https://github.com/RocketChat/developer-docs/tree/416477aacf3193fe1c499552e2eebe39ad0c1878/api/rest-api/methods/livechat/methods/livechat/rooms.md) |
| `livechat/message/:_id` | delete |  |
| `livechat/messages.history/:rid` | `get` | \`\` |
| `livechat/messages` | post |  |

## Offline Message

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/offline.message` | post | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-agent/agent) |

## Page Visited

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/page.visited` | post | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-agent/agent) |

## Room

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/room` | get | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-agent/agent) |
| `livechat/room.close` | post | [Link](https://github.com/RocketChat/developer-docs/tree/416477aacf3193fe1c499552e2eebe39ad0c1878/api/rest-api/methods/livechat/methods/livechat/inquiries.md#livechat-take-inquiry) |
| `livechat/room.transfer` | post | [Link](https://github.com/RocketChat/developer-docs/tree/416477aacf3193fe1c499552e2eebe39ad0c1878/api/rest-api/methods/livechat/methods/livechat/rooms.md) |
| `livechat/room.survey` | post |  |
| `livechat/room.forward` | post |  |
| `livechat/room.visitor` | put |  |

## Transcript

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/transcript` | post | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-agent/agent) |

## Transfer

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/transfer.history/:rid` | get | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-agent/agent) |

## Visitor

| Url | Short Description | Details Page |
| :--- | :--- | :--- |
| `livechat/visitor` | post | [Link](https://developer.rocket.chat/api/rest-api/endpoints/omnichannel-endpoints/omnichannel-livechat-endpoints/livechat-agent/agent) |
| `livechat/visitor/:token` | get | [Link](https://github.com/RocketChat/developer-docs/tree/416477aacf3193fe1c499552e2eebe39ad0c1878/api/rest-api/methods/livechat/methods/livechat/inquiries.md#livechat-take-inquiry) |
| `livechat/visitor/:token` | delete | [Link](https://github.com/RocketChat/developer-docs/tree/416477aacf3193fe1c499552e2eebe39ad0c1878/api/rest-api/methods/livechat/methods/livechat/rooms.md) |
| `livechat/visitor/:token/room` | get |  |


