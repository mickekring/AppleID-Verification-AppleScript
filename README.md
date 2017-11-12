Apple ID Verification SWE
---------------------

### UPDATE: Nov 12, 2017 - No support on this project
I haven't used this since 2015 which means I haven't updated it either. I'll let it live here for a while longer though...

### Purpose & Features

After creating Apple IDs for deploying a large quantity of iOS devices 
we need to go through the time-consuming process of verifying them. This
consists of opening an email, clicking a link and entering the Apple ID
credentials in a form.

### Requirements

- This script is for use with Mail and Safari which exist on every Mac.

- All the verification emails must be on the same mailbox. You can do this
by creating all the Apple IDs using email aliases to one master email.

- All AppleID's must have the same password.

### Instructions

- Edit the script variables at the very top of the script to reflect your 
password and domain.

- Open Safari and Mail.

- Select the first mail to be verified.

- Run script.


### Known Bugs

No checking on whether Mail is open or not. If it is not the script will fail.
