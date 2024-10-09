#  Exercise 2 - Generate an SAP Fiori elements application from an image

In this exercise, we will create a number of **SAP Fiori elements** applications, but instead of using a text document as input, we will instead use images of the applications that we want to create.

## Exercise 2.1 Downloading the sample images into SAP Business Application Studio

From the menu select **View -> Command Palette**

![image](https://github.wdf.sap.corp/storage/user/1340/files/5f4cd483-b113-4d82-adbf-9f67a4445823)

Sarch for command **git clone** and select it.

![image](https://github.wdf.sap.corp/storage/user/1340/files/3eb4f023-ea4e-4003-a5bd-8fdaa5fc7df5)

Paste the repository link below into the input field and hit enter.

```
https://github.com/ianquigley-sap/ai-image-samples
```

Choose the projects folder for the repository location and click **OK**

![image](https://github.wdf.sap.corp/storage/user/1340/files/a79c6fc7-02f4-4b7a-a813-be818d480ae5)

Click **Open** to open SAP Business Application Studio with the new repostiory

![image](https://github.wdf.sap.corp/storage/user/1340/files/9ed70358-4446-4ad5-a9bd-1f6bbcae4563)


## Exercise 2.2 Launching the SAP Fiori tools AI Automated Generator with image input

Similar to exercise 1, ensure that the SAP Fiori tools panel is open with the AI Automated Generator displayed (you can close the **Application Modeler** and **Information** sections):

![image](https://github.wdf.sap.corp/storage/user/1340/files/81a49bf7-4cab-44bb-b726-d0b5f13cb46f)

Click on the **Load file** link

![image](https://github.wdf.sap.corp/storage/user/1340/files/780899cf-84a3-4c3b-aa29-7fe123ada46c)

Select the **countries.jpg** file and click **OK**

![image](https://github.wdf.sap.corp/storage/user/1340/files/484db0d0-8082-44b2-aa84-06192f505f2b)

A thumbnail of the image should appear in the input box.  Click **Generate** to start generate the application directly from the image.

![image](https://github.wdf.sap.corp/storage/user/1340/files/f294415b-f1ba-421f-a10e-e29c8326c46c)

The application will start generating, give it some time

![image](https://github.wdf.sap.corp/storage/user/1340/files/767d0f1d-9c5a-4220-8d05-849a9f57ce4c)

## Exercise 2.3 Previewing the generated application

After generation, click on the **Preview** button to launch a preview of the generated application.  

![image](https://github.wdf.sap.corp/storage/user/1340/files/55df3642-f9b7-445d-b043-38e8bf8a2aca)

You may see a message in the terminal stating that the port is already in use (from previewing our application from exercise 1), click **Return** to use any other port for preview

![image](https://github.wdf.sap.corp/storage/user/1340/files/59183215-8b46-4819-b1df-e1557a739fbf)

The application should launch in a new browser tab. Click **Go** to see the sample data that the AI has created.

![image](https://github.wdf.sap.corp/storage/user/1340/files/834a2d04-294b-43ec-9459-f683d7af15bb)

Navigate back to the tab with SAP Business Application Studio, and click **Accept** to include this project into your workspace

![image](https://github.wdf.sap.corp/storage/user/1340/files/d516cf59-133f-4c47-9617-daf48fca6379)

Click on the **Explorer** icon and you should have a new folder for the project entitled **ai-generated-cap**

![image](https://github.wdf.sap.corp/storage/user/1340/files/353101f6-d3ca-40df-bebc-cf6f251d8f59)

## Summary

You've now successfully generated a SAP Fiori elements application using an sketch of the application you'd like to generate

Continue to - [Exercise 3 - Generate an SAP Fiori elements application using images and text](../ex3/README.md)
