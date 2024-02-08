# dxos ssc QA

We can move these into individual issues once they are validated.

- [iOS build docs](https://github.com/bcomnes/dxos/tree/bcomnes/ios-build/packages/apps/composer-app/docs/ios)

## Video comments

<video src="./img/walkthrough.mp4" width="300"></video>

The header has a positioning bug when the text editor is open.

- UI Is pushed up over the notch safe area
- Buttons are not responsive to touch

<img src="./img/03.PNG" width="300">

<video src="./img/toolbar-bug.mp4" width="300"></video>

When the editor isn't pushing into the safe zone, the header is highly compressed.

The onboarding shortcuts menu is also overflowing.

<img src="./img/03.PNG" width="300">

Using the inspector you can see the misalignment between the DOM and the rendering. Consulting with jwerle to see if this is a platform bug or not.

<img src="./img/04.PNG" width="300">

Comparing to the PWA verison, you can see the safe area is padded out. Also note the editor buttons (and their omission) from the socket build. Not sure whats happening there yet.

<img src="./img/05.PNG" width="300">

Left pannel looks good.

<img src="./img/07.PNG" width="300">

Profile pane looks good

<img src="./img/08.PNG" width="300">

Settings pane is very squished


<img src="./img/06.PNG" width="300">

UI text is selectible in undesirable ways possibly

<img src="./img/09.PNG" width="300">
<img src="./img/10.PNG" width="300">

## Networking

I was able to link devices and the networking worked (tested over LAN).

The link to connected was broken but the invite codes worked across app hosts.

<video src="./img/networking.mp4" width="300"></video>

