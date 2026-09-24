---
title: "Development of an Automated Moderator for Deliberative Events"
collection: publications
permalink: /publications/2024-Development-of-an-Automated-Moderator-for-Deliberative-Events
date: 2024-01-29
venue: 'Neurocomputing, Elsevier'
---

Recommended citation:
Simone Bonechi. Development of an Automated Moderator for Deliberative Events. Electronics. 2024; 13(3):544. ([BibTex](http://clem.diism.unisi.it/~coco_ts/electronics-v13-i03_20240223.bib))
{: style="text-align: justify"}

### Abstract
Online communication platforms have revolutionized interpersonal interactions by transcending geographical barriers. While facilitating connectivity, these platforms have introduced challenges such as overcoming linguistic differences and preventing spam and offensive content diffusion. This is particularly pertinent in the context of deliberative events, where online platforms could be used to extend the inclusion of citizens in democratic decision-making. In traditional deliberative events, human moderators and translators were used to facilitate conversation; however, the need for these figures imposed a limit on both the number of deliberative events that could be organized and the number of participants. In response, this paper proposes an automated moderator for deliberative events. The moderator is developed in Python for the online communication platform Discord and can be used, thanks to the integrated AI (Artificial Intelligence) tools, to automatically manage conversation agendas, prevent spam and inappropriate language, analyze the sentiment of the conversation, and translate messages into multiple languages. In particular, three classifiers, based on a pre-trained BERT (Bidirection Encoder Representations from Transformers), were fine-tuned for spam detection, toxic comments classification, and sentiment analysis. These allow the moderator to automatically detect and remove spam and offensive messages in different languages, send warnings to users, alert administrators, and, after repeated warnings, impose bans. Additionally, a built-in translator, based on Meta’s No Language Left Behind NLLB model, translates messages into five languages (Italian, English, French, German, and Polish). The developed bot was tested in a simulated deliberative event on a Discord server, demonstrating its ability to manage conversations and prevent linguistic abuse.
{: style="text-align: justify"}

You can find the full paper [here](https://www.mdpi.com/2079-9292/13/3/544)
{: style="text-align: justify"}
