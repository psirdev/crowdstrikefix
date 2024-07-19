# Crowdfix 19 July 2024 Outage Resolution

## :question: What's up here?
A recent CrowdStrike update is causing computers running Windows to crash and display the Blue Screen of Death (BSOD). Companies around the world have been unable to reboot, leading to significant disruptions.

If you arrived at work to find chaos, know that you are not alone. Here’s what happened and what to do next.

## :exclamation: But - Why?!
An issue with CrowdStrike's Falcon Sensor product is causing widespread global problems. CrowdStrike engineers are working on the issue, which affects Falcon, the platform designed to stop breaches via a unified set of cloud-delivered technologies.

The IT outage has affected airports, businesses, and big-tech companies.

Microsoft reported taking "mitigation actions" after service issues started at about 6 pm Eastern Time. The company is investigating issues with cloud services in the U.S. and other apps and services.

## :eyes: Workaround Steps
CrowdStrike’s Brody, director of CrowdStrike Overwatch, posted a workaround for the issue:

1. **Boot Windows into Safe Mode or WRE**:
    - Restart your computer.
    - Press `F8` or `Shift + F8` (depending on your Windows version) before Windows starts.
    - Select "Safe Mode" or "Safe Mode with Networking" from the menu.

2. **Navigate to the CrowdStrike Directory**:
    - Open File Explorer.
    - Go to `C:\Windows\System32\drivers\CrowdStrike`.

3. **Delete the Erroneous File**:
    - Locate the file matching `C-00000291*.sys`.
    - Delete the file.

4. **Reboot the Host Normally**:
    - Restart your computer normally.

## What To Do Next
While there is a workaround, it’s not scalable and needs to be applied manually, system by system. This could mean hours or more to get back up and running in a large company.

The issue is hard to resolve once systems are in a reboot loop. Manual fixes take time for system admins to apply since CrowdStrike can't push a new update remotely to fix the issue.

### Possible Solutions
- **Roll Back to Known Good States**: If available, rolling back may help some systems.
- **Manual Intervention**: Manual fixes need to be applied to each system.
- **Out of Band Update or Patch**: If machines can boot in safe mode, an out-of-band update or patch might be possible.
- **Bootable Media Tool**: CrowdStrike might create a tool to apply the fix at the disk level, reducing recovery times for large-scale issues.

## Conclusion
CrowdStrike is communicating the fix as quickly and widely as possible. They are working on solutions to help affected users and may provide tools to ease the recovery process.

## Give me a coffee!
[![Donate with PayPal](https://raw.githubusercontent.com/stefan-niedermann/paypal-donate-button/master/paypal-donate-button.png)](https://www.paypal.com/donate/?hosted_button_id=EHHGTPKA7GQJL)

