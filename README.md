# Agency and Intentions in Language (AIL)

This repository is a template website for AIL workshops.
The README.md file contains some general instructions about how to create your AIL website using GitHub pages.
It is assumed that you are using GitHub in a browser, but you can also clone the repo and modify files locally.
If you need any assistance, feel free to contact Julie Goncharov at julie.goncharov@gmail.com

**Acknowledgement:** html and css files are adapted from the SALT website created by Dylan Bumford and Sarah Murray.

## Step 1: create a new repository for your AIL

The first step is to create a new repository using an existing repository template.

1. In the top right corner, click on the "+" sign and choose "New repository".
1. From the drop down menu, choose a repository template as `ail-workhop/AILn-Workshop-template`.
1. Name your repo, e.g., `AIL1-Workshop`.
1. Click on "Create repository".


## Step 2: modify the head section of your AIL

The website consists of four html pages:

* `index.html` is the entry point with general information about the workshop
* `call.html` is used to publish Call for Papers
* `program.html` is used to publish the program
* `registration.html` is used for announcements about registration and Zoom links

At this step, you need to modify the head section of each html tile with information about your AIL (number, university, dates).
You can also change the colour of the logo (cf. AIL1 with AIL2).

1. Go to your new repo.
1. Go to "Code" and click on `index.html`.
1. Click on the pencil button (middle page to the right) to start editing.
1. Modify lines 6, 8, 10, 20, 24, 29, 32 (use "modify ..." comments as reference).
1. Scroll down to the "Commit changes" section.
1. Write a simple commit message (e.g., "changed headers").
1. Click on the green button "Commit changes".
1. Repeat the same for `call.html`, 'program.html`, and `registration.html`.


## Step 3: modify text/links in `index.html` and `call.html`

At the Call for Papers stage, you only need to modify the text and links in `index.html` and `call.html`.
The Program and Registration pages are set up with TBA messages and will be modified at **Step 6**.

Use the instructions from **Step 2** on how to edit files on GitHub.

* For `index.html`, you need information about
	- invited speakers
	- important dates

* For `call.html`, you need to first set up Call for Papers at EasyChair.


## Step 4: publish your AIL website

You can now publish your AIL website.

1. Go to "Settings > Pages".
1. Under "Build and deployment > Source", choose "Deploy from a branch".
1. Under "Branch", choose "master" and "/root".
1. Click on "Save" (if "Save" is gray-ish, re-choose the "Source" and the "Branch").

Done!

It takes around 15-20 min for a website to build for the first time.
When it is built, a message "Your site is live at <url>..." will appear at the top of the page.

After the first build, all changes you do to html files are published automatically when you commit changes.
These (non-initial) updates do not take long (2-3 min), but remember to re-fresh your browser.


## Step 5: add your AIL to Home

Now, you need to add your AIL to the Home page.

1. Go to the repo called `ail-workshop.github.io`.
1. Edit `index.html` by copy-pasting the following block of code and adjusting it for your AIL:
    ```
    <h4>
      <a href="https://ail-workshop.github.io/AIL2-Workshop/">AIL2</a> Harvey Mudd College
    </h4>
    ```
1. Commit changes.
1. The changes will be published automatically, but it's a good idea to check that the link to your AIL is working live.


## Step 6: update Program and Registration

At some point, you will need to update `program.html` and `registration.html`.

1. Go to your AIL repo.
1. Go to `program.html`.
1. Click on the pencil button to start editting.
1. Delete the block of code that sets the TBA message:
    ```
    <p>
       The program will be added soon.
    </p>
    ```
1. Delete two lines that comment off the program:
    ```
    <!-- UNCOMMENT HERE
    ```
    and 
    ```
    UNCOMMENT HERE -->
    ```
1. Adjust the program as needed.
You can use the `/docs` folder in the repo to keep abstracts and the schedule (in .pdf).
To upload a document to GitHub, go to "Code > Add file > Upload file", choose a file on your computer, write a commit message and click "Commit changes".
It is a good idea to use underscores or hyphens instead of spaces in file names (e.g., name as "AIL1_abstract.pdf" rather than "AIL1 abstract.pdf").
This is because unix based systems are sensitive to spaces and using spaces might cause some trouble.
1. Commit changes.
1. The changes will be published automatically (wait for 2-3 min, remember to re-fresh your browser).
1. Check that all links are working live.

Similarly, update `regisration.html`.


For trouble-shooting see GitHub Pages documentation, Google, or contact Julie Goncharov at julie.goncharov@gmail.com
