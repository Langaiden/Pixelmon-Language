Pixelmon-Language
=================

Language files for Pixelmon

### How to contribute to the translations

First, you need an account here on GitHub.com. Go make one if you have not already!

Got an account? Next up, you need to fork this repository by clicking the Fork button up in the top right corner. This will take you to a new page after it's finished, and the URL will be something like `https://github.com/YourUsername/Pixelmon-Language`. Save that webpage, because you will probably want to go there a lot.

![Finding the Fork button](https://gyazo.com/0ac26712ae962223da0c7e217f670fea.png "Fork button location")

Now you're all set to start translating! Here's how you do it. First you need to find the language you are adding to, for this example we will look at French, but obviously this will be different depending on the language you are translating the mod for. Find the .lang file for the language on your fork's main page.

![Finding the language](https://gyazo.com/b4cae4e6b8f1f4c86dd5196ebf368c0f.png "Finding the language")

Once you're there, you will see a very long text file. To edit it, click the little pencil on the right.

![Finding the edit button](https://gyazo.com/e773f566e3e3039f74a7fccd2ece6bba.png "Edit button")

From here you will go to each lang key (the text to the left of the =) and translate the text on the right of the =. It is very important you do not change what's on the left-side of the equals sign. For example, `item.Ranch Block.name=Ranch Block` will always be `item.Ranch Block.name=[something]`. 

When you are finished with your changes, down the bottom you enter a title for what you have changed, and optionally a description. Then make sure you have `Commit directly to the master branch` ticked, then press `Commit changes`. After that, you'll want to make a 'pull request'. A pull request is what you do when you want your changes to be added to the mod. To make one, first make your way to the pull request tab, then click the New pull request button.

![Find pull request tab](https://gyazo.com/5143477d21ba0ad31c3f5f904e5d1b05.png "New pull request")

After that, it will have a few confusing parts, talking about the base and head. Don't touch any of that scary stuff, just click the nice green button saying Create pull request. Then all you need to do is put in a helpful description, then click the button to create the PR. Eventually, someone with authorisation will check your changes and accept them into the mod. 

#### Updating your language files

When someone has modified the same language file as you, you won't immediately have those changes in your fork. You need to do a pull request in the opposite direction to get updates to yours. You should do this every time you are about to add some translation. First off, get back to the Pull Request screen, as you need to get up to where the confusing Head and Base stuff was. Then, change the left-most repository (The "base") to your repository. It will do a little bit of thinking and then show a slightly different page, but then click the Compare across forks link.

![Compare across forks](https://gyazo.com/0c0edbec66c9074cb078b2c18e8dbad8.png "Compare across forks")

Now you just change the "head" to Pixelmon/Pixelmon-Language. What this does is moves all recent changes from the official repository into your fork. It should end up looking something like this (except instead of "Hiroku" it will have your username)

![What it should look like](https://gyazo.com/84b61624b94820b0977ec1a753e17774.png "What it should look like")

Create the pull request - there should be no need to change the title or description. After you've clicked to create the pull request, it will take you to a page where you need to hit "Merge pull request" which is once again a very nice green button. Press confirm, and it's done! You've updated your fork. Happy translating!
