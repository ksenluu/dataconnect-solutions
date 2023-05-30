---
title: "EngagementMessageMetadataDataset_v0"
description: "Contains Viva Engage message metadata."
author: "ksenluu"
localization_priority: Priority
ms.prod: "data-connect"
---

# Overview

The EngagementMessageMetadataDataset_v0 dataset contains Viva Egnage message metadata.

## Properties
| Name | Type | Description | SampleData | FilterOptions | IsDateFilter | 
|--|--|--| -- | -- |--|
| MessageTenantId | string | Globally unique identifier assigned to the Azure AD tenant. | ```d8af6d5c-1049-d1c3-1add-5d596e8b4691``` |0|false|
| EngagementNetworkId | string | Unique ID for the network that has been used in a few places such as the [Yammer REST API](https://learn.microsoft.com/en-us/rest/api/yammer/rest-api-rate-limits). | ```123456788``` |0|false|
| EngagementMessageId | string | Unique identifier assigned to a message. | ```123456789``` |0|false|
| SenderId | string | Unique identifier assigned to each user of Microsoft Office applications. | ```d8af6d5c-1049-d1c3-1add-5d596e8b4691``` |0|false|
| EngagementThreadId | string | Unique identifier that is assigned to a conversation thread that may consist of multiple messages. | ```4192240070``` |0|false|
| EngagementRepliedToMessageId | string | Unique identifier assigned to the original message that the new message is replying to. | ```3492240070``` |0|false|
| EngagementSenderId | string | Unique identifier assigned to the entity that sends a message | ```1692240070``` |0|false|
| MessageType | string | Parameter that describes the categorization based on the content of the message. (Expected Values: Normal, Praise, Poll, Question, Other).| ```Normal``` |0|false|
| ThreadType | string | Parameter that describes the categorization based on the content of the thread. (Expected Values: Undefined, Question, Story, Other).| ```Question``` |0|false|
| ClientType | string | Parameter that indicates the category of the client or device that is being used to access the application. (Example Values: Web, Desktop, Mobile).| ```Desktop``` |0|false|
| EngagementCommunityId | string | Unique identifier assigned to a community.| ```1321240070``` |0|false|
| IsDirectMessage | boolean | Parameter that is used to indicate whether a message is a private message.| ```true``` |0|false|
| EngagementBroadcastEventId | string | Unique identifier that is assigned to a live Microsoft Teams event.| ```4431240070``` |0|false|
| IsAnnouncement | boolean | Parameter that is used to indicate whether a message is an announcement.| ```true``` |0|false|
| Audience | string | Identifier of the audience to whom the message is posted.| ```YAMMER_PRIVATE_CONVERSATION``` |0|false|
| MessageCreatedDateTime | datetime | Timestamp (UTC) of when a message was created.| ```2017-10-21 16:50:28.914``` |0|false|
| MessageUpdatedDateTime | datetime | Timestamp (UTC) of when a message was updated.| ```2017-10-21 16:50:28.914``` |1|true|
| MessageDeletedDateTime | datetime | Timestamp (UTC) of when a message was deleted.| ```2017-10-21 16:50:28.914``` |0|false|
| ThreadUpdatedDateTime | datetime | Timestamp (UTC) of when a thread was updated.| ```2017-10-21 16:50:28.914``` |0|false|
