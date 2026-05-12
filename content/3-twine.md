---
title: "Activity: Twine"
nav: Twine
topics: twine; interactive narrative; non-linear storytelling
---

<svg xmlns="http://www.w3.org/2000/svg" width="220" height="220" fill="currentColor" viewBox="0 0 16 16" style="display:block;margin:1rem auto 1.5rem auto;">
  <path fill-rule="evenodd" d="M8 5a.5.5 0 0 1 .5.5v3.793l1.146-1.147a.5.5 0 0 1 .708.708l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 1 1 .708-.708L7.5 9.293V5.5A.5.5 0 0 1 8 5"/>
  <path d="M3 0h10a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-1h1v1a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V2a1 1 0 0 0-1-1H3a1 1 0 0 0-1 1v1H1V2a2 2 0 0 1 2-2"/>
  <path d="M1 5v-.5a.5.5 0 0 1 1 0V5h.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1zm0 3v-.5a.5.5 0 0 1 1 0V8h.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1zm0 3v-.5a.5.5 0 0 1 1 0v.5h.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1z"/>
</svg>

## Introduction

In this activity, you'll create a Twine story in which the a grad student researcher arrives in the archives and has to make some decisions about how to conduct their research. 

We'll build the first few passages together, then you'll get a chance to take the story in whatever direction you choose.

By the end, you'll understand how to create branching narratives and use Twine as a fun, effective tool for research communication and teaching. 

---

## Before we begin...

An important note: We will be using the web browser-based version of Twine, which saves stories directly to your browser history, not to cloud storage or your local computer storage. Do not clear your browser history or cache during this session, or you will lose all your work. At the end of the session, you'll publish the story as an HTML file so that it's securely saved on your computer. 

---

## Building the starter scenario

Go to the [Twine website](https://twinery.org/){:target="_blank" rel="noopener"}. Click **Use in your browser**. 

In the menu bar near the top of the page, click **+ New** to create a new story. Name your story "At the Archive" and hit **Create**.

The screen you end up on is your (mostly) blank canvas. Here, you'll build out your story visually, passage by passage, weaving connections together as you go. By default, one passage -- titled **Untitled Passage** is already placed on the canvas. 

Double-click **Untitled Passage**. A text editor will pop up. Click on **Rename** and call this passage **Start**. Next, paste this text exactly as it appears into the text editor: 

> You've just arrived at the archive. It's your first visit. The archivist helps you navigate to the online finding aid. "Take your time, let us know what we can help you with" she says.

> What do you do?

> [[Search through the finding aid carefully]]

> [[Request that the archivist pull the first box you com across]]

The text will save automatically. When you're done, close the text editor by hitting **Esc** on your keyboard. You'll notice that two new passages have been created, with lines connecting them to your **Start** passage. Twine created these passages automatically based on the text you put in [[double brackets]] in your first passage. 

Double click on the **Search through the finding aid carefully** passage and paste this in: 

> You work through the finding aid methodically. Halfway down page three, a folder title stops you cold: "Correspondence, 1943-1944 — unsorted."
> This looks interesting...

> [[Request the unsorted correspondence]]

Now, double click **Request that the archivist pull the first box you come across** passage and paste the following:

> Box one contains 400 pages of committee minutes. Box two is more committee minutes. By box four you've lost track of what you're looking for.

> You pause and pick up the finding aid.

> [[Search through the finding aid carefully]]

You'll notice that this passage did not automatically create a new passage. Instead, an arrow has been drawn from the passage you just edited to the one next to it. We've used [[double brackets]] to call the name of a passage that already exists, therefore making a connection to it, rather than creating a new one.

Now, double click on *Request the unsorted correspondence**. Paste this in:

> The folder arrives. Inside: a series of letters between two researchers who, according to every published history you've read, never corresponded.

> You have forty minutes left before the archive closes.

> [[Take photographs of everything]]

> [[Read carefully and take notes]]

Finally, open each of the two passages you just created and write a brief closing for each. Both should end the story without any further links. 

---

## Play your story

In the toolbar at the top, click **Build** and then **Play**. This will take you to a demo where you can work your way through the story and see how it plays out. Using the back arrow when necessary, make your way through both paths. 

- What does the branching structure imply about the two approaches -- reading first vs. diving right in?
- What does the convergence point (reading carefully) do narratively?

---

## Make it yours

Now that you know how the mechanics work, expand the story in a direction relevant to your own research. 

Some ways to extend on what you've built: 
- **Add a new branch** from one of the existing passages. What happens if the archivist interrupts you? What if the folder is missing?
- **Add a new opening choice** to the **Start** passage. What happens if you choose to do something else? How does the story evolve?
- **Rewrite the scenario entirely** by creating a new Twine project. Use the same (or similar) structure, but set the story in your own research context: a field site, a dataset, an interview, etc.

Keep each passage short. Two to four sentences each is usually more than enough. Don't worry too much about getting the text perfect: at this stage, structure is more important than prose. 

Remember to **Play** your story frequently so that you can make sure it's developing the way you want it to. 

---

## Saving your story

Once you have a working prototype:

Click **Build** in the toolbar, then select **Publish to File**. An HTML file will be automatically saved to your Downloads folder. Double click on the file to make sure it works -- it should open in a playable state in your browser window. 

This file is your finished story in its entirety. You can share it directly with others, or use it in any website you own. 

_Tip:_ You might recall that you learned how to make a GitHub repository into a live website earlier today. You can use those same principles to spin up a website for your Twine story! Create a new GitHub Repository, rename your file "index.html", and drop it into the repository. Then, turn on GitHub Pages, and voila! You now have a very simple website allowing anyone in the world to view and play your Twine story.

---

## Next steps

Twine stories don't have to just be white text on black background. There are a number of customization options you can use to take your stories further. 

- **Text customization:** in the Text editor, you can alter the color, styling, justification, and other features of your text. 
- **Adding images:** images can be embedded using HTML: `<img src="your-image-url.jpg">` 
  - you'll usually want to use URLs of images that are already hosted online. If you're using the GitHub route described above, you can add image files to your GitHub repository and replace "your-image-url.jpg" in the example with the actual filename.
- **Change overall appearance:** under **Story**, click on **Stylesheet**. Here you can add custom CSS to affect the style and appearance of your story. 

You can learn more about all this and other tweaks you can make in the [Twine Cookbook](https://twinery.org/cookbook/){:target="_blank" rel="noopener"}.
