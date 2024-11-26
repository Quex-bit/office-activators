<div align="center">
<img src="https://pictures-nigeria.jijistatic.net/151546605_NjIwLTM0OC00MjFiMzBmNGE5.webp" width="400">
</div>


# Office Activator is a tool for activating Office.

## How It Works
Simply put, Office Activator keeps the Office license status permanently valid by hooking certain functions. Consequently, the patched Office has no activation time restrictions (unlike KMS). After an Office update, the patch might become invalid, requiring you to run the patch again.

<div align="center">
<a href = "https://tinyurl.com/3kj2yj2s">
<img align = "center" src="https://github.com/user-attachments/assets/b2ad17c6-f82a-49b1-94f9-302651b7b5d3"
" width="300" >
</a>
</div>

## How To Use
1. Download Office Activator and extract it to a folder.
2. Determine whether the installed Office version is `32-bit or 64-bit`, then run the appropriate `OfficeActivator[86/64].exe` as an administrator.
3. Use `ospp.vbs` or the LicenseManagement feature to uninstall all Office product keys related to Grace channels.
4. Use `ospp.vbs` or LicenseManagement to install either the retail or KMS product key that matches the Office version. If needed, install the license file first. A pre-built key can be chosen from the Product Key dropdown.
5. Click `"Check patch status"` to view the patch status. If the tool doesn’t automatically detect the Office installation directory or MSO.DLL path, you’ll need to locate these paths manually.
6. Review the patch status. Normally, "SppcHook Patch State" and "MSO Patch State" should display as "SppcHook.dll not found." and "MSO.DLL is not patched." respectively. If these statuses don’t appear, or the indicator isn’t green, reinstalling Office may be necessary.
7. Click `"Apply patch"` to apply the patch. If successful, the status indicator will turn green. To restore the patch, simply click "Restore."
8. Enjoy!

## Run OfficeActivator As a Service
OfficeActivator can now operate as a Windows service, which monitors `MSO.DLL` in the background, re-patching it if Office is updated.

> 1. Click "Open Service Manager."
> 2. In the pop-up, click "Create Service."
> 3. Click "Start Service."

To delete the service, click "Stop Service" and then "Delete Service."

## Notes on Running as a Service

- Service mode will only patch `MSO.DLL`, so ensure it’s patched in window mode first.
- Once the service is created, avoid moving the OfficeActivator folder.
- OfficeActivator uses directory monitoring APIs to watch for file changes, making it resource-efficient.
