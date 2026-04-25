## VATPHIL Updater

The VATPHIL Updater is a desktop application that automatically downloads, installs, and keeps your sector files up to date. It handles everything from first-time installation to AIRAC cycle updates.

### Logging In

When you open the updater, you will be prompted to log in with your VATSIM account.

1. Click **Login with VATSIM** — your browser will open the VATSIM SSO page.
2. Approve the login in your browser.
3. The app will detect the login automatically and bring you to the main screen.

!!! note
    Only controllers authorised by the Philippines vACC staff will be granted access. If you see a "CID not authorised" error and are a active controller, please contact us.

---

### Selecting an Installation Folder

Before installing, you need to point the updater to a folder where your sector files will live.

1. Click **Browse Folder**.
2. Navigate to any location on your computer (e.g. your EuroScope directory).
3. The updater will automatically create a **VATPHIL Sector** subfolder inside your chosen location.

??? tip
    The updater remembers your folder between sessions — you only need to do this once.

---

### Installing / Updating Sector Files

Once a folder is selected, the updater checks the remote files against your local install.

| Status | Button shown | What it means |
|---|---|---|
| Not installed | **Install Update** | No local files found |
| Update available | **Install Update** | New AIRAC Available |
| Up to date | **Force Repair / Reinstall** | Files match the latest release |

Click **Install Update** (or **Force Repair / Reinstall**) to begin. A progress bar at the bottom of the status card will track the download. The files is updated automatically to match the new AIRAC cycle once the install completes.

---

### Entering Your Controller Details

After installing, fill in the **Controller Details** panel in the left sidebar:

| Field | What to enter |
|---|---|
| **Name** | Your name (or CID) |
| **VATSIM CID** | Your VATSIM CID (pre-filled from VATSIM) |
| **VATSIM Password** | Your VATSIM network password |
| **Hoppie ACARS Code** | Your personal Hoppie logon code (optional) |

Click **Apply** when done. 

EuroScope is ready to connect immediately!

!!! warning
    Your VATSIM password is saved locally in `config.json` next to the updater. Do not share this file with anyone.

---

### Selective Repair

If only specific files are missing or corrupted, use **Selective Repair** instead of a full reinstall.

1. Click **Selective Repair**.
2. A window will appear listing all remote files. Missing files are pre-checked and highlighted in red.
3. Check any additional files you want to re-download, then click **Repair Selected**.

---

### Full Reinstall

**Full Reinstall** re-downloads every file from scratch. Use this if your installation is in an inconsistent state.

- Enable **Wipe folder first** to delete all existing files before downloading (useful if you have leftover files from a previous version).
- Click **Full Reinstall** and confirm when prompted.

---

### Keeping the Updater Itself Up to Date

The updater checks for a new version of itself each time you log in. If a newer version is available, you will be prompted to download and install it. The app will restart automatically once the update is applied. no manual steps required.

---
