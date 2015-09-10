# Personal Website
I'm don't find making websites that fun and I don't
want to maintain it regularly. However I do often
add changes to my personal directories, like adding
code and readmes. These additions often reflect what
my current interests are, and I'm in the habit of
making them well documented and complete.

As a high level view, I want to map my personal files,
code, writings, etc, to a website layout so that people
can see what I am doing.

I want to design it so that I never have to take care
of it. At best I want to leave it running and never
look at it again. It will update itself, as I add
content to my local directories, and repositories.

## Design Considerations
I considered using haskell. But I want to have a
working website quickly, so I'm going with the
classic route and using PHP \+ HTML \+ Javascript

## How it works
Source repository at server, possibly using a cron job.
Render page based on the directory layout.

### Elements of page
Simplicity is key.

+ Top bar |El|home|something else|etc|
	+ The top bar will be named after the directories
		at the root.
+ Home page body.

