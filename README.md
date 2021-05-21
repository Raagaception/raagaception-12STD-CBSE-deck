# Raagaception's 12STD CBSE Deck (Science stream, PCM)
[AnkiWeb page](https://ankiweb.net/shared/info/1981482084) | [Latest Release](https://github.com/Raagaception/raagaception-12STD-CBSE-deck/releases/latest) | [Discord Server](https://discord.gg/kbSXsRTUC2)

The **ultimate** Anki deck for preparing for Grade 12 CBSE Board Exams in India!

## Instructions
1) **DOWNLOADS** 
	- Download the Anki program for desktop from [AnkiWeb](https://apps.ankiweb.net/).
	- Download the latest version of the deck from the [latest release changelog](https://github.com/Raagaception/raagaception-12STD-CBSE-deck/releases/latest).
	- Open up the Anki program.
	- Double-click the downloaded deck in system explorer and it will load into Anki.
2) **TUTORIALS AND RESOURCES**
	- Take a deep breath, and try to watch [this YouTube video](https://youtu.be/uLfczzq9z_8) completely to fully understand how Anki functions, and what settings for the learning algorithm might be the best for you. It's pretty long *(30 minutes)* but trust me, it will save you a LOT OF time and trouble later on.
	- After you're done with the video and have set up your recall settings, watch [this YouTube video](https://youtu.be/68DyNKWOj84) to understand what are tags, suspending cards, etc.
	- Finally, watch [this YouTube video](https://youtu.be/iYU-5nXvCrA) to learn about how you can use the tags of the deck to only selectively study the topics *you need*, by suspending all undesired topics. *You don't need to study everything in the deck, just study what you WANT to!*
3) **UPDATES AND CHECKING FOR NEW VERSION**
	- ***WARNING : Make sure you never ever, under any circumstance, rename or rearrange the deck you download from here, otherwise it will hamper the update process. And always make a profile backup before installing any updates!***
	- If you heed the above warning, updating is the most simple part. Head over to the [latest release changelog](https://github.com/Raagaception/raagaception-12STD-CBSE-deck/releases/latest), download the latest version of the deck, and double-click it. It will add all new cards and error corrections to your old version without affecting any of your review information. Only thing you need to do is to go into the card browser, and suspend/unsuspend the newly added chapter cards which you might or might not want to study.
	- To check for updates, bookmark this page and check back to it every 3-ish days, or click the "watch" button on the top-right of repository, or [join my Discord server](https://discord.gg/kbSXsRTUC2) to get pinged for updates.

I will eventually be making a detailed tutorial of my own, when I have the time.

## Tag Structure
This deck follows the special reduced [CBSE 2021 syllabus](http://cbseacademic.nic.in/Revisedcurriculum_2021.html#collapse15), and is tagged accordingly. This deck doesn't consist of the entire syllabus *yet*, but has quite a lot of it covered so far; I'll be still updating it frequently. The tag structure of the latest release is as follows:
- Raagaception_12STD
	- CHEM
		- Ch-01_the-solid-state
		- Ch-02_solutions
		- Ch-03_electrochemistry
		- Ch-04_chemical-kinetics
		- Ch-05_surface-chemistry
		- Ch-07_p-block-elements
		- Ch-10_haloalkanes-haloarenes
		- Ch-11_alcohols-phenols-ethers
		- Ch-12_aldehydes-ketones-carboxylic
		- inorganic-molecular-formulae
		- organic-molecular-formulae
		- random-stuff
	- MATH
		- Ch-01_relations_functions
		- Ch-02_inverse_trig
		- Ch-03_matrices
		- Ch-04_determinants
		- Ch-05_continuity-and-differentiability
		- Ch-07_integrals
		- Ch-10_vectors
		- Ch-11_3d-geometry
			- theory
			- questions
		- Ch-13_probability
			- theory
			- questions
		- random-stuff
		- standard-substitutions-for-integration-differentiation
		- trigonometric-identities-formulae
	- PHY
		- Ch-01_electric-charges-and-fields
		- Ch-02_electrostatic_potential_and_capacitance
		- Ch-04_moving_charges_and_magnetism
		- Ch-08_electromagnetic-waves
		- Ch-09_ray-optics
		- Ch-10_wave-optics
		- Ch-11_dual-nature-of-radiation-and-matter
		- Ch-12_atoms 
		- Ch-13_nuclei
		- Ch-14_semiconductors
		- random-stuff

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
