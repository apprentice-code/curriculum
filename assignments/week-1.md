# Code Apprentice - Assignment Week #1

## Assignment Title: congressional-info

## Instructions:
Before you start work on your assignment complete the following steps to get GitHub setup correctly. This is how you will share your work with your mentor and Code Apprentice.

1. Create a new repo in GitHub titled `congressional-info`
2. Copy the url titled `quick setup` it should start with https:// This will be different for everyone and should should replace `{origin-from-your-github-repo}` with that link.
3. Open a terminal
4. Copy and paste the following commands into your terminal.
	- `cd ~ && mkdir workspace`
	- `cd workspace && mkdir congressional-info`
	- `cd congressional-info`
	- `git init`
	- `git remote add origin {origin-from-your-github-repo}`
	- `git add .`
	- `git commit -m 'init commit'`
	- `git push origin master`
5. Each time you would like to make changes to an assignment and share your work you will need to do this. It will be difficult to start, but you will get use to it in time.

---

### Directions

You're going to create an HTML component to represent a political candidate. Specifically, the representative of your Congressional district. Visit the GovTrack site link below, enter in your home address, and you'll find basic information about your representative.

https://www.govtrack.us/congress/members/map

In your HTML, create an article tag that will serve as your main representative component. Give the element a unique identifier.

    1. In this component, create a sub-component for basic information using the section tag. In this section create elements for the representative's image, name, district info, and political affiliation.
    2. Beneath the basic information, you will create a sub-component, using a section tag, to list any committees the candidate is serving on.
    3. The last component will hold links to any legislation that your representative has enacted.
    4. Upload work to GitHub with the repository name of congressional-info. Remember that this name must be spelled correctly and include the same punctuation to receive credit. If you have any questions about this what so ever please reach out via Slack.

---

Once you have completed the code do the following:

    1. Open a terminal
    2. `cd ~/workspace/congressional-info`
    3. `git add .`
    4. `git commit -m 'finished the assignment'`
    5. `git push origin master`
