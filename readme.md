• You will need to add MessageUI.framework to your project if it is not already included.

• Just add the EmailComposer.h EmailComposer.m  files to your Plugins Folder.

• Place the EmailComposer.js file in your app root, and include it from your html.

• Add to Cordova.plist Plugins: key EmailComposer value EmailComposer

• Example Use:
	window.plugins.emailComposer.showEmailComposer(<subject>, <body>, <reciepient>, <cc recipient>, <bcc recipient>, <is html?>, <attachment url>);