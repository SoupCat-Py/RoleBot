## SETUP

Before RoleBot can be used, you must first set the target role and channel. There are a few things to consider:<br />
- RoleBot's role must be **above** the target role
- Only **voice** and **voice stage** channels are accepted
<br />
Use the following commands to set these variables:

`!set_role ROLE_ID` <br />
`!set_channel CHANNEL_ID` <br />
If your target role or channel could not be found or is invalid, RoleBot will tell you.

Only a specific role can run those commands, and that role has been hardcoded into the bot. Contact Soup Cat (via email or discord) to have it changed.


## USAGE

When a server member joins the target channel, the target role will be applied to them. <br />
When said user switches to another channel or leaves the call entirely, that role will be removed. <br />
If the target channel is changed, any users in the old target channel will **keep** the target role.

**NOTE**: Any user who can run setup commands may also remove the target role manually using the following command:

`!revoke USER_ID` <br />

