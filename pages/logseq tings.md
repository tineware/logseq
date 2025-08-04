- [[quick guide]]
- ## In LogSeq specifically
- LogSeq is built on block-based thinking where indentation creates parent-child relationships
- Indenting content under headers creates actual structural connections in your knowledge graph
- Non-indented headers become "orphaned" blocks that don't build hierarchical relationships
- LogSeq's blcok references allow users to get the full context hierarchy whenever a block is referenced.
-
- contact logseq community for help
  collapsed:: true
	- [Self Hosting Logseq](https://github.com/dustinlacewell/logseq-guide)
	- Make a [Feature Request](https://discuss.logseq.com/)
	- [Check us out on Github](https://github.com/logseq/logseq)
	- [Contribute to Our Docs](https://github.com/logseq/docs)
	- 💬 Message us on [Discord](https://discord.gg/KpN4eHY) (We love feedback!)
	- Ask questions in the [forum](https://discuss.logseq.com)
	- Tweet us [@logseq](https://twitter.com/logseq)
- workflow
  collapsed:: true
	- https://discuss.logseq.com/t/my-logseq-workflow/2278?u=luhmann
	- https://www.reddit.com/r/logseq/comments/uc8l2r/whats_your_method_for_reviewing_notes_on_a/
	- inbox workflow https://www.reddit.com/r/logseq/comments/tdcjjh/does_anyone_use_an_inbox_workflow/
		- To expand on this, you can pretty much replicate GTD with the built in tags:
		  Inbox - TODO
		  Project - DOING [/[project name]/]
		  Up next - NOW
		  Someday - LATER
		  Scheduled - /scheduled
		  Delegated - WAITING [/[delegate name]/]
		- I use an #inbox tag - I then have a query to bring them all together on my main task page (which has all my queries and I keep in the left sidebar.
		- https://discuss.logseq.com/t/how-do-you-handle-single-steps-for-todos/1541/2
		- https://discuss.logseq.com/t/query-for-all-todos-grouped-by-tag/1442
	- logseq calendar https://dynalist.io/d/ao7N0QbfJfDiZ_dNRnW4PI9_
	- resonance calendar from queries https://discuss.logseq.com/t/advanced-queries-creating-a-resonance-calendar-from-queries/2351/2
	- ((63acc7bc-a5d6-4936-b13f-d60e12de01c0))
- ### queries
- can target specific levels of hierarchy.
-
- templates
	- https://thinkstack.club/how-to-set-up-an-automated-daily-template-in-logseq/
	- write a query using the properties and display the result as a table https://twitter.com/logseq/status/1308953181389385728
	- table creation interface https://discuss.logseq.com/t/table-creation-interface-not-query-table/1974
	- [Logseq Customisations for Project Management Template](https://mgw.dumatics.com/logseq-customisation-for-project-management-teamplate/)
	-
	-
- keyboard shortcuts (custom and defaults)
  collapsed:: true
	- `Shift + Cmd + R` — Settings
	- `Ctrl + Shift + R` — Restart
	- `Cmd + Shift + h` — highlight selected text or highlight text entered between wrappers
	- #[[to sort]]
	  collapsed:: true
		- https://discuss.logseq.com/t/keyboard-navigations-shortcuts/366
		  https://discuss.logseq.com/t/customizable-keyboard-shortcuts/146/26
		  https://discuss.logseq.com/t/allow-non-outline-freeform-text/172/36
		  https://discuss.logseq.com/t/vim-mode-powerful-shortcuts/275
		  https://discuss.logseq.com/t/missing-navigation-shortcuts/5769
		  https://discuss.logseq.com/t/keyboard-shortcut-customization-guide/416
		  https://discuss.logseq.com/t/how-to-shift-down-or-shift-up-to-select-the-next-line-in-a-long-block/1310
- styling
	- headers are just visual organization
	- indentation under headers is optional and mainly for visual hierarchy
	- global config.edn
	- config.edn
		- custom macros
		- custom commands
			- [How to write custom slash commands](https://nithinbekal.com/posts/logseq-slash-commands/)
			-
	- custom.css
		- # Header Level 1
		- ## Header Level 2
		- ### Header Level 3
		- #### Header Level 4
		- ##### Header Level 5
		- Highlight 1
		  background-color:: yellow
		- Highlight 2
		  background-color:: red
		- Highlight 3
		  background-color:: pink
		- Highlight 4
		  background-color:: green
		- Highlight 5
		  background-color:: blue
		- Highlight 6
		  background-color:: purple
		- Highlight 7
		  background-color:: gray
		- Normal text
		- *Italic text*
		- **Bold text**
		- Underlined text
		- Strikeout text
		- Ligatures enabled? => --> -> <== ===
		- Reference block
		- Hyperlink
		- Embedded block
		- Tag
		- Page reference
		- examples
			- https://github.com/cannibalox/logseq-custom-files
	- export.css
	-
	- #[[to sort]]
		- https://discuss.logseq.com/t/allow-non-outline-freeform-text/172/32
		- https://discuss.logseq.com/t/doc-mode-on-a-per-bullet-basis/3080
		- https://www.reddit.com/r/ObsidianMD/comments/qvwnp3/how_do_you_personally_decide_when_something/
- sidebar
  collapsed:: true
	- contents? https://discuss.logseq.com/t/toggle-shortcut-for-table-of-contents/3147
	- https://bestofvue.com/repo/mschmidtkorth-logseq-msk-toc-vuejs-table auto gen
- lol there's a book?
  collapsed:: true
	- https://books.google.com/books?id=u35GEAAAQBAJ&pg=PT8&lpg=PT8&dq=how+to+update+existing+page+in+logseq&source=bl&ots=klsFuF5Akg&sig=ACfU3U1o72HGrgitVLMoU0NsD1CfI5xiBA&hl=en&sa=X&ved=2ahUKEwi8z9DmvL_3AhUpkYkEHSmbCw0Q6AF6BAgYEAM#v=onepage&q=how%20to%20update%20existing%20page%20in%20logseq&f=false
	-
- other customizations
  collapsed:: true
	- https://discuss.logseq.com/t/longform-writing-in-logseq/3527
	- flssjkj /block embed [display-label](((searchterm))) 
	  https://discuss.logseq.com/t/how-to-link-to-a-header/2632
	- unofficial documentation for logseq
	  https://mschmidtkorth.github.io/logseq-msk-docs/#/page/Logseq%20-%20Unofficial%20Documentation
	- https://discuss.logseq.com/t/difference-between-pages-pages-and-using-ui-to-create-a-page-with-heading-pages/5484
	- let's understand link/ref/embed
		- https://discuss.logseq.com/t/difference-between-pages-pages-and-using-ui-to-create-a-page-with-heading-pages/5484/4
	- let's understand how to update existing page from daily page in logseq
	- how to write tutorials
	  https://documentation.divio.com/tutorials/
	- learning-oriented docs
	  https://chrislasar.github.io/logseq-doc/docs/tutorial/intro
	- how to write how-to guides
	  https://documentation.divio.com/how-to-guides/
	- problem-oriented docs
	  https://chrislasar.github.io/logseq-doc/docs/how-to/intro
	- nvv w/feats enabled for logseq
	  https://github.com/logseq/nbb-logseq
	- desktop/android app 0.6.7 beta test
	  https://github.com/logseq/logseq/releases/tag/0.6.7
	- numbered bullet points https://discuss.logseq.com/t/css-numbered-lists/387
	- https://discuss.logseq.com/t/outline-overview-for-sidebar/740
	- https://discuss.logseq.com/t/headers-in-markdown-to-become-parent-blocks/5282
	- https://discuss.logseq.com/t/how-to-link-to-a-header/2632
	- https://discuss.logseq.com/t/better-block-page-embed-view/220/3
- tags
  collapsed:: true
	- https://discuss.logseq.com/t/ability-to-delete-or-multiple-delete-pages-from-all-pages-automatic-cleanup-of-accidental-pages/1454/6
	- https://www.reddit.com/r/RoamResearch/comments/fye36i/tags_vs_pageslinks_how_do_you_use_them/
	- https://www.reddit.com/r/logseq/comments/rjmv7w/how_to_style_tags_and_links/
	- https://discuss.logseq.com/t/how-to-query-all-the-tags-without-pages/2706
	- https://www.reddit.com/r/logseq/comments/ppulk4/tagging/
- plugins
  collapsed:: true
	- https://discuss.logseq.com/t/plugin-to-automatically-generate-reminders-for-events-deadlines-etc/1233
- pages: collections of blocks; allow for bidirectional connections
	- [JavaScript Mini-Apps](https://discuss.logseq.com/t/turn-your-pages-into-interactive-applications-javascript-mini-apps-input-output-no-persistent-state/60640) #JavaScript
	- https://discuss.logseq.com/t/difference-between-pages-pages-and-using-ui-to-create-a-page-with-heading-pages/5484/2
	- https://discuss.logseq.com/t/convert-block-to-a-page/649/25
- links to external sites
  collapsed:: true
	- It's also possible to link to pages outside of Logseq, i.e. websites. To point to a URL, either use the trigger menu by typing `/link` or use the keyboard shortcut `Cmd-l` (macOS)/`Ctrl-l` (Windows) to add the following shortcode to the block: `[]()`. Between the brackets (`[ ]`), put the label (name) of the link. Between the parenthesis, put the URL:
		- `[This is the label or name of the link](https://thisistheurl.com)`
- aliases
  collapsed:: true
	- Apart from linking to pages outside of Logseq, you can also use the alias function to link to an internal page. This is handy for when you want to show a different label for an internal link. For example, `[I worked on projects]([[Projects]])` will make the entire "I worked on projects" sentence clickable and point it to the *Projects* page.
	- Finally, for aliases that you use often it's best to add a page alias. For example, you might want the link `[[PKM]]` to point to the page `Personal Knowledge Management`. To do this, add the following in the **first block** of the page `Personal Knowledge Management`: `alias:: PKM`
	- Now, anytime you click a `[[PKM]]` link, you'll end up on the `Personal Knowledge Management` page.