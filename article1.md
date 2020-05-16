# A Sample Page
I will put some simple stuff here.

## Paragrah
A paragraph does not need any special markup. We simply use a blank line to separate two paragraphs. It doesn't matter if we use two or more blank lines, they simply separate two paragraphs and display the same.


## Add, Commit and Push in One Step
When we make a change to an article in a git repository, we need to do the following to publish that change online:

1. Add
2. Commit
3. Push


It's handy if we can do that in just one step, we can create a function in the bash shell, like below:

	function lazygit() {
	    git add .
	    git commit -a -m "$1"
	    git push
	}

Put that above code into .bashrc file and use ". .bashrc" to source the file. Then do the below to publish change in one step with your commit message:

	$ lazygit "publish article2"

That's all. The solution comes from stackoverflow, [see this link](https://stackoverflow.com/a/23328996).


## Program Code
To put a block of program code is simple, just use tab in front of them. Just like above. Inline program code is like this: `a, b = b, a + b`.


## Use an Image
Let's put my image here. Note that when the image cannot be loaded, the alternative text "Image of Russia Mountain" will display. 

![Image of Russia Mountain](images/beautiful-scenery-of-the-mountain-ingushetia-russia-2.jpg)


## Use a Block Quote
Sometimes, we need to refer to a block of text quoted from some other sources, here is how:

> I’ve spent my whole life not only eating food, but working with it as well - I’m passionate about helping people live fuller lives through the food they eat.

> Today, approximately four billion people around the world are not getting the nutrition they need. Two billion of them are not living a full life because they simply don’t have access to food with critical micronutrients like vitamins or minerals.


## GitHub Flavored Markdown
Github offers some legacy markups, some of them are quite useful.


### Tables
Here is a table about my Dell laptop warranty.

Service | Start Date | Expiration Date
--------|------------|-----------------
Prosupport with next business day service | 2020-04-12 | 2021-04-13
Collect and return support | 2020-04-12 | 2021-04-13


### Task Lists
Using a task list to show progres can be handy:

- [x] Summit daily report on 20051 reporting
- [ ] Update website
- [ ] Complete cash report handlingin bochk_revised2

