---
title: "Call a customer in the voice channel | MicrosoftDocs"
description: "Use this topic to understand how you can make customer calls in Omnichannel for Customer Service."
author: mh-jaya
ms.author: v-jmh
manager: shujoshi
ms.date: 11/02/2021
ms.topic: article
ms.service: dynamics-365-customerservice
---

# Call a customer

[!INCLUDE[cc-use-with-omnichannel](../includes/cc-use-with-omnichannel.md)]

To be able to call customers, your administrator must configure outbound calling, add you as user to the outbound capacity profile, and then set up outbound profiles. More information: [Outbound calling](voice-channel-outbound-calling.md)

**To call a customer**

1. In Omnichannel for Customer Service, go to **Contacts**, and then select a customer to call.

2. On the customer summary page, locate the **Mobile Phone** field, and then select the call icon to call the customer.
   The phone dialer opens with the phone number.

3. Select **Call** on the phone dialer.

> [!Note]
> In the **Call** dropdown list, you'll see the phone number that you're making the call from. This is the outbound calling number that'll be displayed on the customer's phone when you make the call.

When the call connects, you'll see the customer details on the conversation page. Based on your outbound calling profile, the transcription and recording starts. If your capacity profile has a limit of one outbound call at a time, you won't be able to make another call when a call is in progress.

## Call customer using the phone dialer

In Omnichannel for Customer Service, you can select the **Launch dialer** phone icon on the menu bar to quickly call a customer. The dialer opens the number pad where you can enter the customer's phone number and then select **Call** to make your call.

### See also

[Overview of the voice channel](voice-channel.md)  
[Use agent dashboard and call controls in the voice channel](voice-channel-agent-experience.md)  
[Make and receive your first call](voice-channel-first-call.md)  

[!INCLUDE[footer-include](../includes/footer-banner.md)]
