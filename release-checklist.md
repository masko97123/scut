To release:

- Make sure notes have been added to changelog.
- Change version number at top of Gruntfile.
- Maybe add old version to `data.yml`.
- Run `grunt version`.
- Build and push a new gem (`gem build scut.gemspec`, `gem push scut...gem`).
- Delete the gem.
- Commit and push.
- Create a tag: `git tag -a vx.x.x -m "[message]"` . ([See these docs](http://git-scm.com/book/en/Git-Basics-Tagging).)
- Push the tag: `git push --tags`.
- Update gh-pages, commit and push it.
- Update Codepen.
- Check.