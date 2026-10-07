# Network-Certification-Labs
Where I will be putting all my research and findings from the Network+ Labs

# Lab 1: Set Up a Windows Computer
Task: Configuring a laptop for a new user (Jaylan), meeting the user's requirements and that system settings comply with company policies.

Steps 1-12: familiarizing myself to the platform. Logging into "Jaylan's" laptop. 

Afterwards, I started working on my tasks. 
  1. Install Portuguese (Brazil) language pack (Jaylan).
  2. Enable high contrast (Jaylan).
  3. Change the computer's name to LAPTOP10 (Bobby's Computer).
  4. Preventing Misuse: Set Jaylan account properties to force a password change and to force the user to change the password periodically thereafter.

1 & 2. Install Language & Change Contrast
<p align="center">
<img width="50%" height="808" alt="Screenshot 2026-10-02 at 6 00 00 PM" src="https://github.com/user-attachments/assets/1e9dfd6c-b941-42c6-8e91-cda9dfa208a9" />
</p>

<p align="center">
<img width="50%" height="798" alt="Screenshot 2026-10-02 at 6 02 11 PM" src="https://github.com/user-attachments/assets/2d984c83-31b5-42c9-8677-59285a043dad" />
</p>

3. Change Laptop Name

<p align="center">
<img width="50%" height="798" alt="Screenshot 2026-10-02 at 6 11 55 PM" src="https://github.com/user-attachments/assets/48004afa-9413-4eaa-b72a-1b8de6c6e9ef" />
</p>

4. Change User Password Properties

<p align="center">
<img width="50%" height="796" alt="Screenshot 2026-10-02 at 6 16 40 PM" src="https://github.com/user-attachments/assets/63f8d368-aacc-420f-b688-f1a15b0ba1f8" />
</p>

Notes/Quiz:
  - Feature that assigns configuration rights and privileges to an account: Groups
  - Methods of fast access to management interfaces: Right-click START, Press START key and type feature name.

# Lab 2: Manage a Windows Computer
Tasks:
  1. Disable device in Windows.
  2. Enable Windows Remote Desktop.

1. Disable device in Windows.
   Signed into the Administer account (Bobby), I was able to use the Device Manager and disable the DVD/CD-ROM drives.

<p align="center">
   <img width="50%" height="794" alt="Screenshot 2026-10-05 at 6 35 17 PM" src="https://github.com/user-attachments/assets/c70d16ec-fd99-406f-a675-4459d55d8f35" />
</p>

2. Enable Windows Remote Desktop.
   Only Admins can do certain tasks/changes to the computer. Picture below is on Jaylan's standard user account.
<p align="center">
   <img width="50%" height="798" alt="Screenshot 2026-10-05 at 6 30 32 PM" src="https://github.com/user-attachments/assets/f339f4fe-70a7-4c5e-a830-3c3529692520" />
</p>

   Picture Below is on the Admin's account (Bobby).

<p align="center">
   <img width="50%" height="803" alt="Screenshot 2026-10-05 at 6 36 40 PM" src="https://github.com/user-attachments/assets/f9d64126-de09-4f23-96f6-f912be8f61eb" />
</p>
   
Notes/Quiz:
  - Change configuration settings, a prompt is shown requesting admin credentials: User Account Control (UAC). Admin's will see a Yes/No prompt.
      - Designed to prevent misuse of admin privleges.  
  - Diver: interface between operating systems and hardware components
  - Powershell cmdlets and objects can be used for automation--run scripts to complete tasks rather than performing them manually.

# Lab 3: Secure a Windows Computer
Tasks:
  1. Verify that Windows Defender features are enabled
  2. Run virus scan
  3. Configure app permissions

  1. In the right corner of the screen, the Window's Defender is enabled. This can be enabled through the Virus & Threat Protection and switching the toggle to on for Real-Time Protection.

  2. Through this window, you can run a virus scan that will scan for malicious software (or malware) and will try to block it from running.

<p align="center">
<img width="50%" height="800" alt="Screenshot 2026-10-06 at 7 56 19 PM" src="https://github.com/user-attachments/assets/838b8a50-d3e4-45a5-8877-83956fd682d3" />
</p>

  3. App permissions:
       - Admin: (needs to) enable(s) the feature/device for access.
       - Standard User: choose to turn on/off for their own personal account.

  Notes/Quiz:
  - Windows Update: mitigates the risk of malicious exploits on the OS.
  - Authentication: (Supported by Windows) Facial & Fingerprint recognition
  - Firewall: security software that enforces rules for allowing/denying network connections.
