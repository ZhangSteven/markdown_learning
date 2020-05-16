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
Let's put my image here. ![Image of Russia Mountain](images/beautiful-scenery-of-the-mountain-ingushetia-russia-2.jpg)



