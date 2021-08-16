**Use Notepad++ for cleaning up CrowdAnki JSON**

1) For fixing UUID
	- Search mode : ``Regular Expression``
	- Find What : ``"deck_config_uuid": ".*"``
	- Replace with : ``"deck_config_uuid": "6fb5f5e9-fcdb-11eb-a062-e0d55e85db11"``
2) For replacing deck description with a placeholder description
	- Search mode : ``Regular Expression``
	- Find What : ``"desc": ".*"``
	- Replace with : ``"desc": "ThisIsADummy123"``
3) For replacing placeholder description with actual description
	- Search mode : ``Normal``
	- Find What : ``"desc": "ThisIsADummy123"``
	- Replace with : ``"desc": "<html>\n<body>\n<h3>Want to get in touch?</h3>\nJoin our <a href=\"https://discord.gg/kbSXsRTUC2\">Discord server</a> or mail at raagaception@gmail.com\n<h3>Want to update your deck to the latest version?</h3>\nCheck out the <a href=\"https://github.com/Raagaception/raagaception-12STD-CBSE-deck/releases/latest\">latest release</a> on GitHub.\n<h3>Any doubts on how to use this deck?</h3>\nRead the tutorial guide on the <a href=\"https://github.com/Raagaception/raagaception-12STD-CBSE-deck/\">GitHub Repository</a>.\n<h3>Found factual errors in a card?</h3>\n<a href=\"https://github.com/Raagaception/raagaception-12STD-CBSE-deck/issues/new?body=%0A%0A%0A---%0A%0AAnki+Note+ID+:%0A\">Submit an issue on GitHub</a> and I&#39;ll check it out immediately. Be sure to include the card ID and note ID of the specific card you find an error in!</li>\n<h3>Want to contribute your corrections and cards in the next update?</h3>\nCheck out the <a href=\"https://github.com/Raagaception/raagaception-12STD-CBSE-deck\">contribution guide</a> on GitHub\n</body>\n</html>"``

... and you're done.