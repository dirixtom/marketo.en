---
unique-page-id: 2359504
description: Use "From Address" A/B Testing - Marketo Docs - Product Documentation
title: Use "From Address" A/B Testing
exl-id: 83e2994b-39ec-4c88-87b0-8f2501ea2bf1
---
# Use "From Address" A/B Testing {#use-from-address-a-b-testing}

You can easily A/B test your emails. One interesting test is the **From Address** test. Here's how to set it up.

>[!PREREQUISITES]
>
>[Add an A/B Test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md)

1. Under the **Email** tile, with your email selected, click on **Add A/B Test**.

   ![](assets/image2014-9-12-15-3a32-3a8.png)

1. A new window opens, select **From Address** for **Test Type**.

   ![](assets/image2014-9-12-15-3a32-3a22.png)

1. If you have previous test information (like a subject test), you can safely click **Reset Test**.

   ![](assets/image2014-9-12-15-3a32-3a28.png)

1. Enter the second **From Address** information you want to test.

   >[!NOTE]
   >
   >Choice A will pre-populate with the information contained in the selected email.

   ![](assets/image2014-9-12-15-3a32-3a34.png)

   >[!TIP]
   >
   >You can click on the **+** to add as many From Addresses as you'd like.

1. Use the slider to choose what percentage of the audience you want in your A/B test and click **Next**.

   ![](assets/image2014-9-12-15-3a33-3a41.png)

   >[!NOTE]
   >
   >The different variations will send to equal portions of the chosen Test Sample Size.

   >[!CAUTION]
   >
   >**We recommend you avoid setting the sample size to 100%**. If you're using a static list, setting the sample size to 100% sends the email to everyone in the audience and the winner goes to no one. If you're using a **smart** list, setting the sample size to 100% sends the email to everyone in the audience _at that time_. When the email program runs again at a later date, any new people who qualify for the smart list will also receive the email since they're now included in the audience.

   OK, we're almost there. Now we need to [define the A/B test winner criteria](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/define-the-a-b-test-winner-criteria.md).
