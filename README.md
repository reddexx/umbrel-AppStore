# ⚠️ COMMUNITY STORE ARCHIVED

## Final Update: Transitioning Away from Umbrel

Dear Umbrel Community and App Developers,

Over the past few months, I have increasingly considered stepping away from the Umbrel ecosystem. Today, I am officially archiving this Community App Store repository. 

While I appreciated the initial vision, the rising number of technical issues and the overall direction of the project's management have caused me to lose interest in continuing my work on Umbrel-related projects and maintaining this store.

### Why I am Leaving Umbrel

Maintaining a stable setup and managing this store became a constant struggle, driven by several core issues:

* **App Stability & Limitations:** Keeping installed apps running reliably was a continuous challenge. Furthermore, Umbrel's restrictive environment made creating, testing, or publishing new apps incredibly frustrating and limited.
* **Storage Bloat:** Over time, system storage bloated unnecessarily. Umbrel lacks built-in, user-friendly cleanup mechanisms to manage and purge cached or redundant docker data.
* **Broken Backup & Restore System:** The final straw was the "Rewind" system, which failed to work reliably. Attempting to restore my setup on a fresh Umbrel instance failed completely, and the system refused to remount my existing storage.

### Moving Forward with 1Panel

As of **July 2026**, I have fully migrated my infrastructure to **1Panel**. The transition has been night and day, as it provides the core functionalities I desperately missed in Umbrel:

* **Seamless Container Deployment:** Deploying and managing Docker containers works flawlessly.
* **Robust Backups:** Creating and restoring backups—whether for the entire system or individual apps—is reliable and straightforward.
* **System Maintenance:** It includes built-in tools to easily clean up and optimize system storage.
* **Advanced Networking:** Features like **MACVLAN** work out of the box without complex workarounds.
* **Open Ecosystem:** Installing and managing apps via their App Store is smooth and completely unrestrictive.

---

### Repository Status & Forking

This Community Store repository is now **permanently archived**. 
* No new apps will be accepted.
* Existing apps will no longer receive updates or support from my side.

If anyone from the community wishes to take over, maintain, or keep the apps alive, **you are highly encouraged to fork this repository** and submit it as a new custom store path in Umbrel.

Thank you to all the developers and users who supported this community store along the way. I wish you all the very best!

Best regards,  
**Reddexx**
