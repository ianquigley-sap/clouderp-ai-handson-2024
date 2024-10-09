# Getting Started - Setting up your Development Environment

As a particpant of the hands-on, you should already be setup with access to the SAP Business Application Studio landscape below which you can use as your development environment.

## Accessing SAP Business Application Studio

Navigate to https://bcjoule.cry10cf.int.applicationstudio.cloud.sap/index.html?externalRedirect=true

## Creating the Development Space

Click on the button **Create Dev Space**.

![Create Dev Space](https://github.wdf.sap.corp/storage/user/1340/files/6a25acaf-8b35-4a5d-b676-72971c711139)

Enter a name for your development space and select application profile **Full Stack Cloud Application**.

![Select Profile](https://github.wdf.sap.corp/storage/user/1340/files/2a624f6f-830f-4662-8c2f-73b89bf67137)

In the lower right corner of the page press button **Create Dev Space**.

![Confirm](https://github.wdf.sap.corp/storage/user/1340/files/2662b9a9-177e-41a0-95b6-f23c929175ec)

Once your development space has status running, click on the development space name to open it.

![Enter Dev Space](https://github.wdf.sap.corp/storage/user/1340/files/9bfae3a8-66c7-4f12-95c9-64aeb015fd89)

Clixk **OK** in the popup window to accept the tracking settings in the newly created dev space.

![image](https://github.wdf.sap.corp/storage/user/1340/files/30286051-fd6e-4c12-b53a-55fb714a12b5)


## Enable Generative AI features with SAP Fiori Tools

Next you will need to enable the feature toggle to allow for generative AI with SAP Fiori tools.  Please follow these steps:

1. Click on the three lines icon in the top left hand side of the window.
2. Select **File**
3. Select **Preferences**
4. Then select **Settings**

![image](https://github.wdf.sap.corp/storage/user/1340/files/7045a247-78d4-43a6-8c6f-bb53c9d8095d)


Click on the file icon in the top right of the screen to enable the settings file to appear.

![image](https://github.wdf.sap.corp/storage/user/1340/files/3edf378c-bbf8-4a97-a0d8-6aa42e788ad4)

You will be presented with a blank file apart from 2 curly braces:

![image](https://github.wdf.sap.corp/storage/user/1340/files/f19b0e4e-5467-4d1a-b4b0-3df7b2252ead)

Between the curly braces, enter the text:

```JSON
"sap.ux.help.testBetaFeatures.enableFioriAI": "165a0e31-35ea-4bee-8d47-b8593435a82d"
```

Your file should look as follows:

![image](https://github.wdf.sap.corp/storage/user/1340/files/13c5a99c-7a90-40f1-acbe-4a7dc80186b1)

Click on the `x` to close the settings window.

## Open your project folder

Open the explorer icon from the left hand side:

![image](https://github.wdf.sap.corp/storage/user/1340/files/3afa5c88-d970-45d8-91d9-99667eb714ff)

And select **Open Folder** button

![image](https://github.wdf.sap.corp/storage/user/1340/files/7fa61653-5c0e-41c8-90c4-9738ed335ebe)

Select the **Projects** folder from the drop down

![image](https://github.wdf.sap.corp/storage/user/1340/files/97a75930-60a4-4568-82fe-4abbfbb2dfb8)

Click **OK** and your window will reload

![image](https://github.wdf.sap.corp/storage/user/1340/files/c8c7b520-2eae-4e2d-84b5-3888c2a165c2)

## Summary

With the setup procedure done, you now have completed:

- Access to SAP Business Application Studio
- Creation of your development space
- Enabling of the SAP Fiori tools AI features

Continue to - [Exercise 1 - Generate an SAP Fiori elements application from business requirements](../ex1/README.md)



