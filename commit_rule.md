### git commit rule

1. Use Imperative Verbs & Meaningful Messages & Summarize with a Subject Line

2. Use Atomic Commits & Regular Commits

3. Include Tests in Commits

4. Avoid Committing Generated Files

5. Link to External Resources or Mention the Issue Number

6. Use Commit Hooks for Standards or Follow a Template

a commit message template is like

`:*emoji*:[*type*] *description*`

types list:

- doc

	document update

	emoji :memo:

- bad

	bad code for temp work around, need to fix later

	emoji :poop:

- code

	source code update

- bug

	fix bug

	emoji :bug:

- tune

	performence improve

	emoji :zap:

- script

	build script etc. update

	emoji :hammer:

- test

	test code update

	emoji :white_check_mark:

- style

	format code or restruct dir etc.

	emoji :recycle:

- kick-off

	first commit for repo or project

	emoji :tada:

- dependency

	update dependency version or relative

	emoji :arrow_down: :arrow_up: :pushpin:

- release

	mark tag or milestone

	emoji :bookmark:

- revert

	revert changes

	emoji :rewind:

- config

	update non-code configuration file

	emoji :wrench:

- misc

	other not mentioned case

	emoji :alien:

emojis reference: [gitmoji.dev](https://gitmoji.dev)


7. Update Commit Messages use `git amend` instead of adding a new commit

8. Be Consistent

9. Add Co-authors (when necessary)
