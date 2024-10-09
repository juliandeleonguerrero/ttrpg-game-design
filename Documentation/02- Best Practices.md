---
tags:
  - documentation
---
# Introduction

While "best practice" is a matter of opinion, following these tips will help keep your notes organized, and in general aid in your worldbuilding 

# Best practice for your notes

## Headers

Headers are **the most important way** you can organize content within a single note. With headers, you can:

- Form a basic table of contents for your notes
- Split information up into relevant sections.
- And within Obsidian.md, "fold" header sections, allowing you to see or hide information as deemed useful.

If you have seen the left-hand outline in Wikipedia articles, the outline is being generated off of the headers within that Wikipedia article.

![[wikipedia-outline.png]]

This very article includes extensive use of headers to break up each section. You can see how it is helpful for outlining this note in the screenshotted outline pane below:

![[headers-outline.png]]

You can even jump to specific sections by selecting that section in the note's outline.

If you don't know how to use/write headers in markdown, Obsidian.md's documentation on [headers and markdown formatting](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Headings) is recommended reading.

## Tagging

Notes can be given tags. For example, this note is tagged "documentation". Tags can be used to help sort and find content in your Obsidian worldbuilding vault regardless of their folder location, and even allow you to generate useful insights about your vault with Obsidian's Graph View, and various third-party plugins.

When making or using a tag, the highest priority is that the tag is readable. Making them shorter is ideal, but less important.

![[tags-example-gods.png]]

The templates that come with this worldbuilding vault are already pre-tagged, but feel free to add or edit tags as desired in your notes. Just remember they 

If you're using this vault to manage a longer narrative, such as a TTRPG campaign or book, you may find it useful to tag content specific to an arc or section with that arc's name or arc number.

## Templates

There are several template notes included within this vault. They can be inserted using Ctrl+Shift+i to create an appropriate structure and tags within an article.

It is strongly recommended to use these to keep organization within the vault consistent. If you find yourself editing a note's organization a lot after inserting a template, it is recommended you just edit that template. Information about templates and Obsidian's support for them can be found [here](https://help.obsidian.md/Plugins/Templates).

# Vault Best Practices

## BACKUP YOUR WORK

Always make sure you are backing up your work! If your data gets wiped and you lose dozens of hours, that work is probably gone for good. Don't let this happen to you!

Obsidian's documentation specifies several different ways of both syncing your data, as well as backing it up. I strongly recommend reading through it [here](https://help.obsidian.md/Getting+started/Back+up+your+Obsidian+files). Going in blindly with typical cloud backup services can result in many complications to your Obsidian vault.

*Note: If you are technically savvy, you may find using git a great backup choice. For more information, see [[04- Git and Obsidian]].*

## File Organization

For general worldbuilding, organizing your files and folders is straightforward, and there is documentation within the folder note of each section on how you can organize the content. 

### TTRPG Campaigns

But if you are using this worldbuilding template for TTRPG campaigns, organizing files and folders can get complicated. 

For example, in a typical worldbuilding vault, you might organize locations within a world by continent, then by region/kingdom, then by smaller region/location and so on. This falls apart if you have important notes for your campaign many folders deep. If this isn't a problem for you, that's fine. If it is a problem for you, consider arc-specific folders.

#### Story arc-specific folders within general world folders

Important worldbuilding elements of your campaign can still be documented elsewhere. But for campaign-specific content, you might make a section for a specific arc (generally a range of levels) within the characters folder, location folder, etc. 

From there, campaign-specific notes can be sorted into the appropriate folders. If you find a note would be better elsewhere later on, that's fine- there's no harm to moving a note after the fact.

Here's an example of how the folder and file organization might look in practice.

**Example:**

- Characters
	- Political Figures folder
	- Gods folder
	- 01- First Arc folder
		- (Character note for character in first arc)
		- (Character note for another character in first arc)
- Locations
	- Continents folder
	- Planes of Existence folder
	- 01- First Arc folder
		- (Location note for location in first arc)
		- (Location note for another location in first arc)

#### Parent arc folders

Alternatively, you might have a parent story arc folder, with character, location, etc. folders inside of that. The advantage of doing it this way is that you reduce clutter within your main worldbuilding folders- sometimes a shopkeeper will only be relevant for that arc, and may not matter for your overall worldbuilding. 

Here's an example of what that might look like:

**Example:**

- Characters folder
- Documentation folder
- Events folder
- Etc...
- First Arc folder
	- Locations folder (for first arc)
	- Characters folder (for first arc)
	- Etc.