Turn any Android or IOS phone into an two way SMS gateway to send and receive SMS anywhere in the world.

This extension integrates https://telerivet.com/ with allowing you to use SMS anywhere that you can send and receive SMS.

## Requirements

A Telerivet account with `API key` and `Project ID`. These can be configured by logging into https://telerivet.com/ and clicking on My account.

## Installation

1. Download the latest release from https://github.com/3sd/org.ndi.sms.telerivet/releases to your extensions directory
2. Browse to **Administer > System Settings > Extensions**
3. Find **Telerivet SMS integration** and click **Install**

Note: for help on installing extensions, consult the [extensions chapter of the CiviCRM system administrator guide](https://docs.civicrm.org/sysadmin/en/latest/customize/extensions).


## Configuration

2. Configure a new SMS provider at civicrm/admin/sms/provider?reset=1
3. Choose Telerivet for the name.
4. Add your api key and project id into the API parameters box as follows
```
api_key=##############################
project_id=#################
```
5. Other fields on the SMS provider form are not used, but are required by CiviCRM. Add anything you like into these fields.
6. Set the callback URL in Telerivet as follows `http[s]://[YOUR_SITE_URL]/civicrm/sms/callback?provider=org.ndi.sms.telerivet`

## Getting started

Once you have installed and configured this extension, you are ready to send SMS via Telerivet. Consult the [CiviCRM user guide for more information on using SMS in CiviCRM](https://docs.civicrm.org/user/en/latest/sms-text-messaging/what-is-sms/).  

## Credits

This extension has been written by [Michael McAndrew](https://twitter.com/michaelmcandrew) from [Third Sector Design](https://thirdsectordesign.org/) who you can [contact](https://thirdsectordesign.org/contact) for help, support and further development.

## Contributing

Contributions to this repository are very welcome. For small changes, feel free to submit a pull request. For larger changes, please create an issue first so we can talk about your ideas.

## License

This extension is licensed under [AGPL-3.0](LICENSE.txt).
