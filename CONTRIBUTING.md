# General Issue Guidelines

Please remember, an issue is **NOT** a feature request.
An issue is either a bug, a link that is sending you to the wrong place, another feature that isn't working as intended, or a question about the site.
Also, please precisely describe the issue.
If you can't understand the issue, but just know something is wrong, just give us the location where the bug is happening.
Please use as much detail as possible as to what causes the issue, where the issue is, an how it affects the website.
Also, please make sure you tag the issues, for our sanity.
If you think you can fix your issue yourself, we absolutely encourage you to do so!
Contributing to a project like this is a great way to keep yourself engaged in coding, which transitions perfectly into...

# Pull Request Guidelines

We have some general guidelines we'd like you to follow when adding to or editing the site.
If you think your pull request might be exempt from these rules, post it as an issue with the question tag.

Guidelines:

* Please do not remove anything without first consulting us through an issue marked with the question tag. Changing something by removing the original and adding your own does not count as removal
* You are only allowed to edit files inside the /docs folder. This means no editing this file, mkdocs.yml, readme, or others outside of that folder.
* Please format your additions similarly to how we have ours. If you add info on a bit, keep it under the correct subheading, unless it's general info on that bit.
* Have fun!

# How to Contribute

In order to contribute, you're going to need a current version of Python 3, really anything will work, and the packages noted in requirements.txt.

Fork the repository onto your own account, and clone it to your computer in whatever fashion you prefer.
You can use github's editor, but we really don't recommend it, as you won't be able to test changes in mkdocs' live test server.

To install the packages in requirements.txt, open your terminal, navigate to the folder where requirements.txt is located, and run

`pip install -r requirements.txt` 

This will install both mkdocs and the cinder theme, and you will be able to test all your changes.

To find more information on mkdocs, check out their official [site](https://www.mkdocs.org/), and for info on writing in Markdown, check out [https://www.markdowntutorial.com/](https://www.markdowntutorial.com/).