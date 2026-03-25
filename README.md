WATCH THIS VIDEO HERE!!!!!!

<https://loom.com/share/547bf402188a4cb5bd658dd6092b22e7>
## Hosting a Static Website in Azure

### Objective

This SOP outlines the steps to create a resource group and host a static website in Azure.

### Key Steps

 

**1. Create a Resource Group** [0:00](https://loom.com/share/547bf402188a4cb5bd658dd6092b22e7?t=0)

![Create Resource](https://github.com/user-attachments/assets/68a793c5-d994-448b-b738-678c19294ef3)


- Go to the Azure portal.
- Click on 'Create a resource'.
- Select 'Resource Group'.
- Name your resource group (e.g., RGLab01).
- Click 'Review + Create'.
- Click 'Create'.

 

**2. Create a Storage Account** [0:47](https://loom.com/share/547bf402188a4cb5bd658dd6092b22e7?t=47)

![Create Storage](https://github.com/user-attachments/assets/9de2550f-fb83-4de6-89b4-7445b6f780eb)


- In the Azure portal, navigate to 'Storage Accounts'.
- Click on 'Create'.
- Choose the resource group you just created.
- Name your storage account (e.g., your chosen name).
- Select 'Locally Redundant Storage (LRS)' for cost efficiency.
- Click 'Review + Create'.
- Click 'Create'.

 

**3. Enable Static Website Hosting** [2:00](https://loom.com/share/547bf402188a4cb5bd658dd6092b22e7?t=120)

![Enable Static Website](https://github.com/user-attachments/assets/d524be5f-5a04-4e5c-9ba0-435a5fa29152)


- In your storage account, scroll down to 'Data Management'.
- Click on 'Static Website'.
- Enable static website hosting.
- Set 'Index Document Name' to 'index.html'.
- Set 'Error Document Path' to '404.html'.
- Click 'Save'.

 

**4. Create and Upload HTML File** [2:25](https://loom.com/share/547bf402188a4cb5bd658dd6092b22e7?t=145)

![Create and Upload HTML file](https://github.com/user-attachments/assets/e3e4fdb9-cf98-4d49-87d9-d13d401d9708)


- Create your HTML content using any HTML editor or generator.
- Save the file as 'index.html' on your desktop.
- In the Azure portal, navigate to 'Containers' under your storage account.
- Click on 'Upload' and select your 'index.html' file.
- Confirm the upload.

 

**5. Access Your Static Website** [4:00](https://loom.com/share/547bf402188a4cb5bd658dd6092b22e7?t=240)

![Access you Static Website](https://github.com/user-attachments/assets/d776e1cd-2f69-48c9-8717-ac34c8e0b54f)


- Go back to the 'Static Website' section in your storage account.
- Copy the URL provided for your static website.
- Open a new browser tab and paste the URL to access your website.

### Link to Loom

<https://loom.com/share/547bf402188a4cb5bd658dd6092b22e7>
