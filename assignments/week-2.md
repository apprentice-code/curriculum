# Code Apprentice - Assignment Week #2

## Assignment Title: animal-planet

## Instructions:

Before you start work on your assignment complete the following steps to get GitHub setup correctly. This is how you will share your work with your mentor and Code Apprentice.

1. Create a new repo in GitHub titled `animal-planet`
2. Copy the url titled `quick setup` it should start with https:// This will be different for everyone and should should replace `{origin-from-your-github-repo}` with that link.
3. Open a terminal
4. Copy and paste the following commands into your terminal.
	- `cd ~ && mkdir workspace`
	- `cd workspace && mkdir animal-planet`
	- `cd animal-planet`
	- `git init`
	- `git remote add origin {origin-from-your-github-repo}`
	- `git add .`
	- `git commit -m 'init commit'`
	- `git push origin master`

---

### Directions

You're going to create a single HTML page to share information regarding 6 different animals within the same genus.
https://en.wikipedia.org/wiki/Genus

Example:

Genus: Felis different species:

- Felis catus
- Felis Chaus
- Felis Silvestris
- Felis Nigripes
- Felis Margarita
- Felis Bieti

In your HTML, create a section tag for each species.
Complete the following for each species:

1. In each section identify the species with a header tag.
2. Embed an image in each section, this image should be an image of the species.
3. Create an unordered list under the image. Within this unordered list, list 3 different traits of this species. Make sure to title the list.
4. Provide the conservation status under neath each trait list. This should be within a div.
5. Provide a link to the corresponding wikipedia page for each animal. This should be an embedded link with the text “More Information” inside of a button HTML element.
6. Upload work to GitHub with the repository name of animal-planet. Remember that this name must be spelled correctly and include the same punctuation to receive credit. If you have any questions about this what so ever please reach out via slack.

---

Once you have completed the code do the following:

1. Open a terminal
2. `cd ~/workspace/animal-planet`
3. `git add .`
4. `git commit -m 'finished the assignment'`
5. `git push origin master`
