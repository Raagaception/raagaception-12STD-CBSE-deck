# Raagaception's 12STD CBSE Deck (Science stream, PCM)
[AnkiWeb page](https://ankiweb.net/shared/info/1981482084) | [Latest Release](https://github.com/Raagaception/raagaception-12STD-CBSE-deck/releases/latest) | [Discord Server](https://discord.gg/kbSXsRTUC2)

## Table of contents

- [**Introduction**](#introduction)
- [**Getting started**](#getting-started)
	- [Installing Anki and setting up the CrowdAnki addon](#installing-anki-and-setting-up-the-crowdanki-addon)
	- [Installing the deck for the first time](#installing-the-deck-for-the-first-time)
	- [Selectively studying from desired topics](#selectively-studying-from-desired-topics)
	- [Setting up the review settings](#setting-up-the-review-settings)
- [**Updating to a new version of the deck**](#updating-to-a-new-version-of-the-deck)
- [**Contributing your own cards and edits to this deck**](#contributing-your-own-cards-and-edits-to-this-deck)
	- [Setting up your GitHub account and GitHub desktop](#setting-up-your-github-account-and-github-desktop)
	- [Exporting as JSON via CrowdAnki](#exporting-as-json-via-crowdanki)
	- [Creating a fork and committing changes](#creating-a-fork-and-committing-changes)
	- [Pushing your changes to our repository for review](#pushing-your-changes-to-our-repository-for-review)
- [**MathJax render script for AnkiWeb users**](#mathjax-render-script-for-ankiweb-users)
- [**Support Us**](#support-us)

---

## Introduction
The largest, most comprehensive, community maintained flashcard deck for [Anki](http://ankisrs.net/) on the internet, featuring:
- Over **1600 cards** from Chemistry NCERT, spanning Organic Chemistry, Inorganic Chemistry, and Physical Chemistry.
- Over **600 cards** from Physics NCERT, spanning topics from effects of electricity to Optics to Semiconductors.
- Over **500 cards** from Math NCERT, covering most of the equations needed in solving calculus, trigonometry, and various other topics.
- Community contributions using [CrowdAnki](https://github.com/Stvad/CrowdAnki), so anyone with a GitHub account can fact check cards, provide corrections, and even upload their own cards from any topic, be it for CBSE boards, JEE Mains, or the SATs.
![](https://i.imgur.com/1fUGGME.gif)

---

## Getting started
First-time here? Welcome! 👋 Following all the steps given below will get you up and running.

### Installing Anki and setting up the CrowdAnki addon

1. New to Anki? You need to first set up the program.
	- Go over to the [AnkiWeb website](http://ankisrs.net/), scroll down, download the latest version for your operating system, and install it on your PC.
1. In order to install and later upgrade _Raagaception's 12STD CBSE Deck_, you'll need to first install an Anki add-on called "CrowdAnki".
	- Open Anki on your computer, go to the ``Tools`` menu and select ``Add-ons``.
	- In the dialog box, click on ``Get Add-ons...`` and paste in the following code : ``1788670778``
	- Click on ``OK`` to install the add-on, and close the Anki program.
You're now ready to install the deck itself!

### Installing the deck for the first time

1. Open Anki, go to the ``File`` menu and select ``CrowdAnki: Import git repository``.
1. In the dialog box, paste in the link to this repository : ``https://github.com/Raagaception/raagaception-12STD-CBSE-deck``. Wait for a little while as CrowdAnki imports the deck for you. **Don't panic if Windows shows that Anki isn't responding**, just give it a little time.
1. Don't change anything in the _CrowdAnki Import Settings_ dialog box that opens; just press ``OK`` to start the import. A dialog box should then confirm that the import was successful.
1. The deck must now be visible on your profile. Close Anki fully and reopen it before doing anything else.

### Selectively studying from desired topics
You don't need to study everything in the deck, just study what you WANT to; since the deck is painstakingly arranged topic-by-topic, and chapter-by-chapter.
Here's how to go about studying by utilizing that to your advantage :
1) Open the "Browse" window and scroll down the left pane.
1) Under the ``Decks`` section, click on ``Raagaception's 12STD CBSE Deck``. This will now display a list of the thousands of cards available in the deck.
1) Select all cards in browser with ``(Ctrl+A)``, then suspend ALL the cards in the deck - this will result in none of the cards showing up in your review queue. Note that all suspended cards are represented in the browser as yellowed-out cards.
1) Expand the ``Raagaception's 12STD CBSE Deck`` listing by using the arrow icon. Keep expanding the list to reveal more and more subtopics.
1) When you find the ones you want to unsuspend, select the listing, which will bring up the cards from **that topic only**. Press ``Ctrl+A`` to select all cards in the browser, and ``Ctrl+J`` to unsuspend them. 
1) You can now close the browser and review the cards normally, until you wish to unlock newer topics. To do that, just repeat all the steps from step 4).

### Setting up the review settings

If you're a beginner to Anki, I recommend watching [this YouTube video](https://youtu.be/uLfczzq9z_8) to fully understand how Anki functions, and what settings for the learning algorithm might be the best for you. It's pretty long, but trust me, it will help you understand how the Anki review settings actually work.

Here's how to apply the settings I personally use to study this deck, if you need a guideline. Feel free to play with it and find the settings which best work for you.
1. Open Anki, and click the tiny ⚙️ icon to the right side of the deck name, and click ``Options``.
1. Go to the dropdown on the top-right of the "_Options for Raagaception's 12STD CBSE Deck_", click ``Add Preset`` and give it a name.
1. Here's how I set my settings for when I was studying for my CBSE 12th boards. The settings in **bold** have to be compulsorily copied as it is, at least for using this particular deck. Feel free to tailor the rest of the settings to your needs, as you see fit :
#### Daily Limits
- New cards/day = ``100`` (Depends on how close your exam is. Take the total number of cards in deck, divide it by the number of days left to your next major exam - you'll get the number which can roughly tell you what to set new cards per day to.)
- **Maximum reviews/day** (MANDATORY!) = ``9999`` (Set this to the maximum number possible so as to not impede Anki's algorithm. Finish all available reviews daily if you want to utilize Anki to it's max.)
#### New Cards
- Learning steps = ``15m 1h 1400m``
- Graduating Interval = ``3``
- Easy Interval = ``4``
- **Insertion order** (MANDATORY!) = ``Random``
#### Lapses
- Relearning steps = ``1h 1d``
- Minimum interval = ``1``
- Leech threshold = ``6`` (This declares the number of times you've to get a card wrong for Anki to declare it as a Leech)
- **Leech Action** (MANDATORY!) = ``Tag Only``
#### Display Order
- **New card gather priority** (MANDATORY!) = ``Ascending position``
- **New card sort order** (MANDATORY!) = ``Random``
- New/review priority = ``Show before reviews``
- Interday learning/review priority = ``Mix with reviews``
- **Review sort order** (MANDATORY!) = ``Due date, then random``
#### Burying
- Bury new siblings until the next day = ``On``
- Bury review siblings until the next day = ``Off``
#### Advanced
- Maximum interval = ``60`` (This really depends on you. This sets the longest duration in days beyond which your reviews can't be scheduled, anything over this limit overrides the Anki algorithm.)
- **Starting ease** = ``2.50``
- **Easy bonus** = ``1.30``
- **Interval modifier** = ``1.00``
- **Hard interval** = ``1.20``
- **New interval** = ``0.20``

---

## Updating to a new version of the deck

1. Keep in mind that updating the deck **OVERWRITES** all edits and structural changes you might have made to the deck on your end. If you wish to get your changes included in the public version of the deck, check out [how to contribute your edits for the next update](#contributing-your-own-cards-and-edits-to-this-deck).
1. Open Anki, and rename your existing "_Raagaception's 12STD CBSE Deck_" to something like "_OLD Raagaception's 12STD CBSE Deck_"
1. Now follow the same steps as [**installing the deck for the first time**](#Installing-the-deck-for-the-first-time)
	- There's a chance you might get a dialogue box which looks similar to this :
		![](https://i.imgur.com/qB70Afa.png)
	- If you get this, simply change the ``New note type`` to ``Basic-Raagaception`` if it's a basic card type (that is, has the fields ``Front`` and ``Back``) or to ``Cloze - Raagaception`` if it's a cloze card type (that is, it has the fields ``Text`` and ``Extra``)
		![](https://i.imgur.com/iGEcA4h.png)
1. After the import, you'll notice that all your existing cards have been automatically shifted to "_Raagaception's 12STD CBSE Deck_". At this point you can safely delete the now empty "_OLD Raagaception's 12STD CBSE Deck_".
2. Close Anki fully and reopen it before doing anything else.

👉 To stay informed of new releases, make sure to [watch this repository's releases](https://help.github.com/en/articles/watching-and-unwatching-releases-for-a-repository), or join us on our [Discord server](https://discord.gg/kbSXsRTUC2) to get pinged whenever new updates are release.

---

## Contributing your own cards and edits to this deck
Since this deck uses [CrowdAnki](https://github.com/Stvad/CrowdAnki), anyone with a GitHub account can help in correcting errors on cards and adding new cards from topics which are not already covered in the deck. If you're inclined to sincerely do so, then read on.

### Setting up your GitHub account and GitHub desktop

1. If you're completely new to GitHub, you need to [sign up for a new account](https://github.com/signup). For the purpose of this tutorial, I'll be using a dummy account by the name of ``Demo-User-42069``.
1. Next, download and install [Github desktop](https://desktop.github.com/). 
1. Open GitHub desktop, and go to ``File > Options`` and click on ``Sign in``. Hit ``Continue with Browser`` on the next dialogue window.
1. This will open your browser. Choose ``GitHubDesktop.exe`` and click ``Open Link``. Click ``Authorise`` on the subsequent browser dialogue.
	![](https://i.imgur.com/MEimTAu.png)
1. Click ``Clone a respository from the Internet``, and enter the URL of this repo, that is, ``https://github.com/Raagaception/raagaception-12STD-CBSE-deck``. Specify the directory where you wish to clone the repository. 
	- For example, I'm going with ``C:\GitHub Repositories\raagaception-12STD-CBSE-deck``. 
		![](https://i.imgur.com/1LWdFzW.png)

### Exporting as JSON via CrowdAnki
1. Now comes the slightly confusing part - exporting with CrowdAnki from Anki. Open Anki, and read carefully.
	- If you've just **edited** some errors on the cards from the public deck, then directly proceed to step 3.
	- If you wish to add **new cards** to this deck, then put your cards into individual decks categorized by subtopics (try to categorize them to the best of your ability, we'll manage the rest during review). Create a new deck with your account's name, put the subtopic decks under that. Now put the deck with your GitHub username under ``3.GitHub Contributions Held for Review``.
		- For example, if my GitHub username is ``Demo-User-42069``, and I want to contribute two decks, namely ``Inorganic Group-16`` and ``Vectors``, both meant for JEE aspirants, then this is what my structure should look like : ![](https://i.imgur.com/nyHGMYZ.png). **Please don't put your contributions under any other section, otherwise they'll get overwritten by updates.**
1. Click the tiny ⚙️ icon to the right of _Raagaception's 12STD CBSE Deck_, and click ``Export``. 
1. Change the export format to ``CrowdAnki JSON representation (*directory)`` 
	![](https://i.imgur.com/suu5qSQ.png)
1. Make sure all settings look exactly like the image below, then hit ``Export...``
	![](https://i.imgur.com/8xXzv82.png)
1. xport into any directory you wish, and remember the location. 

### Creating a fork and committing changes
1. Go to the export location, change the name ``deck.json`` to ``raagaception-12STD-CBSE-deck.json``. Then copy all the folder contents. 
	![](https://i.imgur.com/LCCK7Oy.png)
1. Open GitHub desktop, and click ``Show in Explorer`` 
	![](https://i.imgur.com/kmJmG9M.png). 
1. Paste the copied files there, and select ``Replace the files in the destination`` when prompted. 
	![](https://i.imgur.com/Bpji4ck.png)
1. Now when you open GitHub desktop again, you'll see something like this : 
	![](https://i.imgur.com/dtcw3rM.png)
1. In the bottom right corner, click ``Create a fork``, and click ``Fork this respository`` on the subsequent dialogue box.
	![](https://i.imgur.com/zLD5PXg.png)
1. Select ``To contribute to the parent project`` and click ``Continue``
	![](https://i.imgur.com/eKvS7EV.png)
1. In the bottom right corner, write a heading and description and feel free to describe your contribution in detail, which will help us in categorizing it. Then click ``Commit to main``
	![](https://i.imgur.com/lh2rSUP.png)

### Pushing your changes to our repository for review
1. Whenever you're ready to finally submit your contribution to us on GitHub, click ``Push Origin``
	![](https://i.imgur.com/DRbb2ni.png)
1. Open GitHub, and go to your **forked** repository. In my case, it's named ``demo-user-42069/raagaception-12STD-CBSE-deck``. Click ``Contribute`` and then click ``Open pull request``.
	![](https://i.imgur.com/OC9Mv7D.png)
1. Click ``Create Pull Request`` 
	![](https://i.imgur.com/QXPdkhC.png)
1. Make sure ``Allow edits by maintainers`` is ticked, then ``Create Pull Request``.
	![](https://i.imgur.com/5mO9xJ0.png)

When you see the following screen, you've successfully submitted your contribution. Congratulations! Wait a few days for us to review and categorize it, and then your contribution will get included in the next update. ![](https://i.imgur.com/LrvZZyy.png)

---

## MathJax render script for AnkiWeb users
If you wish to review your cards on the browser version of AnkiWeb, the MathJax equations in any cards won't get rendered. But by adding the following code to the front and back of the "Basic - Raagaception" and "Cloze - Raagaception" card templates, AnkiWeb will render your MathJax for you : 
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

---

## Support Us
This project is made with ❤️ by the community, to help all Science higher secondary students worldwide to ace their exams. You can support us by 
- Taking out some free time to [contribute to the development of this deck](#contributing-your-own-cards-and-edits-to-this-deck).
- [Starring](https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars) the project on GitHub
- Joining our ever-expanding [Discord server](https://discord.gg/kbSXsRTUC2)
- Leaving a review on the deck's [AnkiWeb page](https://ankiweb.net/shared/info/1981482084)
- By spreading the word around. Share this repository's link to anyone you know who might benefit from using it!

---
---