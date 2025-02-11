# Google-4-TbSync

This provider add-on adds Google synchronization capabilities to [TbSync](https://github.com/jobisoft/TbSync). Only contacts and contact groups are currently managed, using Google's People API. There's currently no plan on supporting calendars.

The work is partly based on [EteSync4TbSync](https://github.com/etesync/EteSync-4-TbSync), [DAV4TbSync](https://github.com/jobisoft/DAV-4-TbSync), [gContactSync](https://github.com/jdgeenen/gcontactsync) and advices by [John Bieling](https://github.com/jobisoft) himself.

## Current status and roadmap / Known limitations

What already works:
* Google-to-Thunderbird creation / update / deletion of contact groups;
* Google-to-Thunderbird creation / update / deletion of contacts;
* Google-to-Thunderbird creation / update / deletion of contact group members.
* Thunderbird-to-Google creation / update / deletion of contact groups;
* Thunderbird-to-Google creation / update / deletion of contacts;

What is missing:
* Thunderbird-to-Google creation / update / deletion of contact group members. Please note that for this to be fixed the undergoing port of TbSync to WebExtension must be completed first: only then this add-on will be partially rewritten and will be able to fully manage contact group memberships.

A full working version ~~could probably be ready by~~ ~~June / July 2021~~ ~~September~~ ~~the end of 2021~~ will be ready a few months after the new TbSync is released.

## How to use it

You first need to [install TbSync](https://addons.thunderbird.net/addon/tbsync) and [generate your own Google API Console project credentials](https://github.com/zanonmark/Google-4-TbSync/wiki/How-to-generate-your-own-Google-API-Console-project-credentials). Then do one of the following:

### Download an official release

.xpi packages can be downloaded from [Thunderbird Add-ons](https://addons.thunderbird.net/addon/google-4-tbsync), or through the _Thunderbird_ > _Tools_ > _Add-ons_ menu.

### Test the latest code

1. [Grab the latest .zip package](https://github.com/zanonmark/Google-4-TbSync/archive/refs/heads/main.zip).
2. Unzip it wherever you want.
3. Load it as a temporary add-on from _Thunderbird_ > _Tools_ > _Add-ons_ > cog icon > _Debug Add-ons_ > _Load Temporary Add-on_ (pick _manifest.json_ for example).
4. Test it, preferably using the _Read-only mode_ option (see below).

## Warning

* Even if early reports seem to confirm the add-on is working properly, the project is still in its early development stage: **backup both your Google and Thunderbird address books before running the software!**
* **You are strongly suggested to [use the _Read-only mode_ option](https://github.com/zanonmark/Google-4-TbSync/wiki/Account-options#read-only-mode)**.

## Additional information

Please refer to the [wiki section](https://github.com/zanonmark/Google-4-TbSync/wiki) for other useful information, including [FAQ](https://github.com/zanonmark/Google-4-TbSync/wiki/FAQ-(Frequently-Asked-Questions)), guides and user contributions.
