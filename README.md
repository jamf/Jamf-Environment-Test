# No Longer Maintained
Recommended to use [JamfCheck](https://marketplace.jamf.com/details/jamfcheck)
![JamfCheckLogo](images/JamfCheck.png)

## Jamf-Environment-Test
![Jet Logo](images/Jet_Icon.png)

Utility for testing an network environments for successful communication from Apple Devices to Apple and Jamf hosted services

This tool is designed to be used by an Apple admin in conjuction with a networking admin on a network that the Apple device will be on.

It will report on current device proxy settings, and its connectivity to Apple urls listed [here](https://support.apple.com/en-us/HT210060)

This application is designed to run on a macOS device only.

It doesn't require any Administrator privileges, it will query a collection of urls and display some relevant device information

The output report is a html file that will be automatically opened upon completion of the application run

Raw version of the bash script is availble for validation

Full app can be found [here](https://github.com/jamf/Jamf-Environment-Test/releases/latest)

How to use Wiki can be found on the [Wiki](https://github.com/jamf/Jamf-Environment-Test/wiki)

### Important
when downloading with Chrome you may see the following error 

![Dangerous](images/dangerous.png)

This is expected due to Google Chrome's security, to proceed with the download click the arrow and then Keep

![Dangerous Keep](images/dangerous_keep.png)

_Note: this tool is open source and is not supported by the Jamf support team_
