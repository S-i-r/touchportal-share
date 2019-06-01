# Button with Corner

_This is based on the highly recommended [180+ Free Key Icons pack by Nerd or Die](https://nerdordie.com/product/stream-deck-key-icons/)_

I wasn't satisfied with the included .PSD for this, so I've recreated a more versatile .PSD for anyone to create their own buttons. If your button is a decent quality (good resolution and design), you may contribute to this pack by making a Pull Request with your additions.

#### This pack is created by **Sir**

* Discord: Sir#0001

# Template Usage
I recommend exploring template.psd with the Border layer visible.
### PSD Groups and Layers:
* Group: Template - The whole thing. Useful to duplicate to create a new button
	* Group: Icon - I put icons (such as logos and so on) in here. Purely for organization.
	* Group: Corner - Lower-right corner. If you wish to have a solid-colored corner.
		* Object: Hollow Corner - Corner piece is "hollow" on the inside
		* Object: Solid Corner - Corner that is completely solid
	* Object: Border - This is the surrounding border of the icon
	* Group: Button Interior - contains the interior/main area of the button.
		* Group: Without Corner - Masked. If you _don't_ want your corner area to share your button background, put your desired background in here.
			* Layer: ^ Place Background Here ^ - Just a white background with help-text.
		* Group: With Corner - Masked. If you _do_ want your corner area to share your button background, place your desired background in here.
		* Layer: ^ Place Background Here ^ - Just a white background with help-text.
* Group: Example - An example button in action.
* Text Layer: Information - Just a blurb of information to get back to the repo.