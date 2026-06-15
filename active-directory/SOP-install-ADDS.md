## SOP — Install Active Directory Domain Services on a Windows Virtual Machine

### Objective

This SOP explains how to install Active Directory Domain Services (AD DS) on a Windows Server virtual machine using Server Manager. Following these steps will prepare the server for later domain controller configuration.
🎥 Video walkthrough: [Watch on Loom](https://loom.com/share/dcfd85958dd54b7db031ce7e5c37fe63) — timestamps below link to each step.

### Key Steps

**1. Open Server Manager and wait for the dashboard to load** [0:09](https://loom.com/share/dcfd85958dd54b7db031ce7e5c37fe63?t=9)

![generated-image-at-00:00:09](https://loom.com/i/d413180f2e774f7c902de189b732ed11?workflows_screenshot=true)

- Launch **Server Manager** on the Windows Server virtual machine.
- Wait until the **Dashboard** fully loads before making changes.
- Confirm you are working from the correct server instance before continuing.

**2. Start the Add Roles and Features Wizard** [0:37](https://loom.com/share/dcfd85958dd54b7db031ce7e5c37fe63?t=37)

![generated-image-at-00:00:37](https://loom.com/i/b4ed2afa6088416cbf07781066ebd4c8?workflows_screenshot=true)

- In **Server Manager**, select **Manage**.
- Click **Add Roles and Features** to open the wizard.
- Review the introductory screen, then click **Next** to continue.

**3. Select Active Directory Domain Services for installation** [0:37](https://loom.com/share/dcfd85958dd54b7db031ce7e5c37fe63?t=37)

![generated-image-at-00:00:37](https://loom.com/i/b4ed2afa6088416cbf07781066ebd4c8?workflows_screenshot=true)

- In the roles list, locate and select **Active Directory Domain Services**.
- When prompted, proceed with the installation workflow.
- Click **Next** to move through the wizard screens.

**4. Add required features and confirm installation** [0:48](https://loom.com/share/dcfd85958dd54b7db031ce7e5c37fe63?t=48)

![generated-image-at-00:00:48](https://loom.com/i/53475da957d44008951755f1dcff8b14?workflows_screenshot=true)

- When the wizard prompts you to add required features, click **Add Features**.
- Continue by clicking **Next** through the remaining screens.
- Click **Install** to begin installing **Active Directory Domain Services** and its dependencies.

**5. Verify the installation completes successfully** [1:05](https://loom.com/share/dcfd85958dd54b7db031ce7e5c37fe63?t=65)

![generated-image-at-00:01:05](https://loom.com/i/f765a25d5f204805bb939cc43f4bf3ec?workflows_screenshot=true)

- Wait for the installation process to finish.
- Confirm the role installation completes without errors.
- Return to Server Manager and verify that **Active Directory Domain Services** is now installed.

### Cautionary Notes

- Ensure you are logged in with an account that has sufficient administrative privileges.
- Do not close Server Manager or interrupt the installation while it is in progress.
- Installing AD DS is only the first step; additional configuration may be required afterward to promote the server to a domain controller.

### Tips for Efficiency

- Keep Server Manager open and use it as the central place for role installation and verification.
- Before starting, confirm the VM is stable and fully booted to avoid interruptions.
- If you plan to continue with domain controller setup, document the server name and any installation prompts for reference.

### Link to Loom

<https://loom.com/share/dcfd85958dd54b7db031ce7e5c37fe63>
