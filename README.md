# Raagaception's 12STD CBSE Deck (Science stream, PCM)
[AnkiWeb page](https://ankiweb.net/shared/info/1981482084) | [Latest Release](https://github.com/Raagaception/raagaception-12STD-CBSE-deck/releases/latest) | [Discord Server](https://discord.gg/kbSXsRTUC2)

The **ultimate** Anki deck for preparing for Grade 12 CBSE Board Exams in India!
![](https://i.imgur.com/Z2EW3NQ.gif)

## Instructions
1) **DOWNLOADS** 
	- Download the Anki program for desktop from [AnkiWeb](https://apps.ankiweb.net/).
	- Download the latest version of the deck from the [latest release changelog](https://github.com/Raagaception/raagaception-12STD-CBSE-deck/releases/latest).
	- Open up the Anki program.
	- Double-click the downloaded deck in system explorer and it will load into Anki.
2) **REVIEW SETTINGS**
	- Take a deep breath, and try to watch [this YouTube video](https://youtu.be/uLfczzq9z_8) completely to fully understand how Anki functions, and what settings for the learning algorithm might be the best for you. It's pretty long *(30 minutes)* but trust me, it will save you a LOT OF time and trouble later on.
	- Here are the settings I personally use to study this deck, if you need a guideline:
		![](https://i.imgur.com/rphVCR5.gif)
3) **STUDYING TOPIC-WISE BY TAGS**
	- *You don't need to study everything in the deck, just study what you WANT to;*   since I've tagged my deck chapter-by-chapter.
	- Here's how to go about studying by utilising the tag system :
		1) Open the "Browse" window and scroll down the left pane.
		2) Click on the parent tag "Raagaception_12STD", select all cards in browser *(Ctrl+A)*, then suspend ALL the cards in the deck - this will result in none of the cards showing up in your review queue. Note that all suspended cards are represented in the browser as yellowed-out cards.
		3) Select each tag corresponding to the topic you wish to study, select all the cards which come up in the browser *(Ctrl+A)*, then unsuspend them. Only the unsuspended topics will appear in your review queue.
		4) Close the browser and review the cards normally for a few days. If you wish to unlock more chapters, just repeat step b. <br>![](https://i.imgur.com/WWT4vUu.gif)
4) **UPDATES AND CHECKING FOR NEW VERSION**
	- ***WARNING : Make sure you never ever, under any circumstance, rename or rearrange the deck you download from here, otherwise it will hamper the update process. And always make a profile backup before installing any updates!***
	- If you heed the above warning, updating is the most simple part. Head over to the [latest release changelog](https://github.com/Raagaception/raagaception-12STD-CBSE-deck/releases/latest), download the latest version of the deck, and double-click it. It will add all new cards and error corrections to your old version without affecting any of your review information. Only thing you need to do is to go into the card browser, and suspend/unsuspend the newly added chapter cards which you might or might not want to study.
	- To check for updates, bookmark this page and check back to it every week, or click the "watch" button on the top-right of repository if you have a GitHub account, or [join my Discord server](https://discord.gg/kbSXsRTUC2) to get pinged for updates.

## Syllabus Covered
This deck follows the special reduced [CBSE 2021 syllabus](http://cbseacademic.nic.in/Revisedcurriculum_2021.html#collapse15), and is tagged accordingly. This deck doesn't consist of the entire syllabus *yet*, but has quite a lot of it covered so far; I'll be still updating it frequently. The syllabus covered as of the latest release is as follows:
- *Physics*
	- *Electrostatics*
		- Ch-01 Electric Charges and Fields
		- Ch-02 Electrostatic Potential and Capacitance
	- *Electromagnetism*
		- Ch-04 Moving Charges and Magnetism
	- *Electromagnetic Induction and Alternating Current*
		- Ch-06 Electromagnetic Waves
	- *Optics*
		- Ch-09 Ray Optics
		- Ch-10 Wave Optics
	- *Dual Nature of Matter*
		- Ch-11 Dual Nature of Radiation and Matter
	- *Atoms and Nuclei*
		- Ch-12 Atoms
		- Ch-13 Nuclei
	- *Electronic Devices*
		- Ch-14 Semiconductors
- *Chemistry*
	- *Physical Chemistry*
		- Ch-01 The Solid State
		- Ch-02 Solutions
		- Ch-03 Electrochemistry
		- Ch-04 Chemical Kinetics
		- Ch-05 Surface Chemistry
	- *Inorganic Chemistry*
		- Ch-07 p-Block Elements
	- *Organic Chemistry*
		- Ch-10 Haloalkanes and Haloarenes
		- Ch-11 Alcohols, Phenols and Ethers
		- Ch-12 Aldehydes, Ketones and Carboxylic Acid
- *Mathematics*
	- Ch-01 Relations and Functions
	- Ch-02 Inverse Trigonometry
	- Ch-03 Matrices
	- Ch-04 Determinants
	- Ch-05 Continuity and Differentiability
	- Ch-07 Integrals
	- Ch-10 Vectors
	- Ch-11 Three Dimensional Geometry
	- Ch-13 Probability

## Support and Updates
If you spot a mistake, have a suggestion or want to help, please don't hesitate to [submit an issue](https://github.com/Raagaception/raagaception-12STD-CBSE-deck/issues/new?body=%0A%0A%0A---%0AAnki+Card+ID+:%0AAnki+Note+ID+:%0A). I'm constantly adding more topics and simplifying this deck to aid comprehension.

## MathJax Script for AnkiWeb Users
If you're reviewing your cards on the browser version of AnkiWeb, the equations in any cards won't get rendered. But by adding the following code to the front and back of the "Basic - Raagaception" and "Cloze - Raagaception" card templates, AnkiWeb will render your MathJax for you : 
```css
<script type="text/x-mathjax-config">
MathJax.Hub.processSectionDelay = 0;
MathJax.Hub.Config({
messageStyle:"none",
showProcessingMessages:false,
tex2jax:{
inlineMath: \[ \['$','$'\], \['\\\\(','\\\\)'\] \],
displayMath: \[ \['$$','$$'\], \['\\\\\[','\\\\\]'\] \],
processEscapes:true
}
});
MathJax.Ajax.config.path\["mhchem"\] =
"https://cdnjs.cloudflare.com/ajax/libs/mathjax-mhchem/3.3.2";
MathJax.Hub.Config({
TeX: {
extensions: \["\[mhchem\]/mhchem.js"\]
}
});
</script>
<script type="text/javascript">
(function() {
if (window.MathJax != null) {
var card = document.querySelector('.card');
MathJax.Hub.Queue(\['Typeset', MathJax.Hub, card\]);
return;
}
var script = document.createElement('script');
script.type = 'text/javascript';
script.src = 'https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS\_SVG-full';
document.body.appendChild(script);
})();
</script>
```

This code was included in the initial versions of the deck but discontinued from v0.9.0 onwards to maximize compatibility, since on versions of Anki 2.1.40 or lower, this JavaScript [causes a rendering error](https://i.imgur.com/KfQRJZZ.png). Hence if you need the functionality, and you use Anki version 2.1.42+, you can manually add it yourself.

## Contributors
A huge thanks to my peers [Avery](https://ankiweb.net/shared/byauthor/1383206786) and [Skillustrator](https://github.com/The-Skillustrator) for providing their assistance in the creation of this project!
