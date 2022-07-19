Ubiquiti decided to introduce [ads in UniFi](https://user-images.githubusercontent.com/820984/114285060-feca0380-9a08-11eb-9940-cd23629eb785.png), which is a privately-hosted web app to manage some Ubiquiti devices.  This ad blocker list blocks ads in UniFi from any site location.

To add this list to uBlock Origin, open uBlock's settings page and click on the "Filter lists" tab.  At the bottom of the page, expand the "Custom" tree and check the "Import..." box.  Then, add this URL to the textarea that appears:

    https://raw.githubusercontent.com/synthead/unifi-adfree/master/unifi-adfree.txt

Click the "Apply changes" button on the top-left of the page, and you're done!  This URL reflects the latest commit to this list, so your ad blocker will auto-update accordingly.

This list can be used on all the other common ad blockers too, but they have their own settings page that I won't get into detail about.  If you don't know about [uBlock Origin](https://ublockorigin.com), you might consider switching to it as it's fast, light, and is [GPL-licensed](https://github.com/gorhill/uBlock/blob/master/LICENSE.txt).
