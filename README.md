## Project Overview
Simulated a Tier 1 help desk password-change scenario using a Windows 10 workstation joined to a Windows Server 2016 Active Directory domain.

## Lab Environment
- Virtualization: Oracle VirtualBox
- Domain Controller: Windows Server 2016
- Client: Windows 10 (Wins10-Lab-01)
- Domain: rodneylab.local
- Test Account: RODNEYLAB\itsupport01

## Issue
A domain user was prompted to change their password during Windows sign-in.

## Resolution Workflow
1. Identified the domain password-change prompt.
2. Completed the password change using the current credentials.
3. Confirmed Windows reported the password was successfully changed.
4. Signed into the Windows desktop.
5. Ran `whoami` in Command Prompt to verify the domain account.

## Results
The password change was successful, and the workstation session was authenticated as `rodneylab\itsupport01`.

## Skills Demonstrated
- Windows domain authentication
- Active Directory account support
- Password-change procedures
- Command-line verification
- Help desk documentation

## Evidence
Screenshots of the password-change prompt, successful password change, and domain login verification are provided in the screenshots folder.

*This project was completed in a personal virtualized lab using a simulated support scenario.*
