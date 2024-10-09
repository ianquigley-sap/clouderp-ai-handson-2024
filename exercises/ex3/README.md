#  Exercise 3 - Generate an SAP Fiori elements application using images and text


In this exercise, we will create an **SAP Fiori elements** application using a document that contains both text and images, so that the required application can be best described.


## Exercise 3.1 Uploading the business requirement document with images

In the explorer in SAP Business Application Studio, expand the **transport-request-distribution** folder and right click on the **requirement0.md** file (1).  Then click on the **Open Preview** link (2).

![image](https://github.wdf.sap.corp/storage/user/1340/files/14081d74-4836-4618-bd93-4ca056540161)

You should then see a document that includes a mixture of text and images.  This document will detail what should be in the list page of your application, and also what should be in the object page that gets displayed when a user selects an item from the list

![image](https://github.wdf.sap.corp/storage/user/1340/files/a2864317-49ec-43ce-b8a6-f87853684695)

Similar to the previous exercises, click on the SAP Fiori tools icon to open the panel with the AI Automated Generator displayed (you can close the **Application Modeler** and **Information** sections):

![image](https://github.wdf.sap.corp/storage/user/1340/files/81a49bf7-4cab-44bb-b726-d0b5f13cb46f)

Click on the **Load file** link

![image](https://github.wdf.sap.corp/storage/user/1340/files/780899cf-84a3-4c3b-aa29-7fe123ada46c)

Click into the **transport-request-distribution** folder

![image](https://github.wdf.sap.corp/storage/user/1340/files/dce537ef-4999-4f6c-b98d-ca8d2a9f044a)

Select the **requirement0.md** file

![image](https://github.wdf.sap.corp/storage/user/1340/files/113b5f5c-6c73-40f6-84ac-1177c5472090)

The text of the file will be populated into the text box.  Click **Generate** to start generating your application.  This will take some time.

![image](https://github.wdf.sap.corp/storage/user/1340/files/54ddc1a7-ac2d-41eb-ba04-31f62eac9294)

## Exercise 3.2 Reviewing the generate application from a business requirement document with images

After generation completes, click on the **Preview** button to launch a preview of the generated application.  

![image](https://github.wdf.sap.corp/storage/user/1340/files/55df3642-f9b7-445d-b043-38e8bf8a2aca)

You may see a message in the terminal stating that the port is already in use (from previewing our application from exercise 1), click **Return** to use any other port for preview

![image](https://github.wdf.sap.corp/storage/user/1340/files/59183215-8b46-4819-b1df-e1557a739fbf)

A new browser tab should open with the generated application.  Click on the **Go** button to display the items

![image](https://github.wdf.sap.corp/storage/user/1340/files/dd09513c-8979-4eb6-9f23-e38d51d6ae3d)

Select an item from the list and the object page should display with the details:

![image](https://github.wdf.sap.corp/storage/user/1340/files/c127f4f9-5b33-458b-ba6e-e96a44a4d80c)

Navigate back to the tab with SAP Business Application Studio, and click **Accept** to include this project into your workspace

![image](https://github.wdf.sap.corp/storage/user/1340/files/d516cf59-133f-4c47-9617-daf48fca6379)

Click on the **Explorer** icon and you should have another new folder for the project, this time entitled **ai-generated-cap-1**

![image](https://github.wdf.sap.corp/storage/user/1340/files/23891d0c-ef46-4ec6-80f7-3b037034c5dc)

## Summary

In this exercise you have seen how the Fiori AI generator can use both text and images to create detailed **SAP Fiori elements** applications.

Continue to - [Exercise 4 - Other sample images for Generation](../ex4/README.md)
