# How to Build and Test Documentation Locally

This guide explains how to build and preview the Solve It Now! documentation site on your local machine using Jekyll.

## Prerequisites

- **macOS or Linux** (Windows users can use WSL)
- **Ruby 2.7+** (Recommended: use [rbenv](https://github.com/rbenv/rbenv) or [rvm](https://rvm.io/))
- **Bundler** and **Jekyll** gems installed
- **Git** installed

## 1. Install Ruby (if needed)

If you don't have Ruby 2.7 or newer:

```bash
brew install rbenv
rbenv install 3.2.2
rbenv global 3.2.2
```

Restart your terminal and verify:

```bash
ruby -v
# Should show ruby 3.2.2 or newer
```

## 2. Install Bundler and Jekyll

```bash
gem install bundler
gem install jekyll
```

## 3. Install Project Dependencies

Navigate to the documentation directory:

```bash
cd $HOME/dev/solve-it-now/docs
bundle install --path vendor/bundle
```

## 4. Build and Serve the Site Locally

```bash
bundle exec jekyll serve
```

- The site will be available at `http://localhost:4000/solve-it-now/` (or similar).
- You will see build warnings about Sass deprecations—these do not affect functionality.

## 5. Preview the Site

- Open your browser and go to `http://localhost:4000/solve-it-now/`
- Or, in VS Code, open the Simple Browser (`Cmd+Shift+P` → "Simple Browser: Show") and enter the URL above.

## 6. Auto-Regeneration

- Jekyll watches for changes and automatically rebuilds the site.
- Just refresh your browser to see updates after editing Markdown files.

## 7. Troubleshooting

- **Ruby version errors:** Make sure you are using Ruby 2.7+ (`ruby -v`).
- **Missing gems:** Run `bundle install --path vendor/bundle` again.
- **Native extension errors:** Install Xcode Command Line Tools: `xcode-select --install`
- **Port conflicts:** If port 4000 is busy, use `bundle exec jekyll serve --port 4001`.

## 8. Stopping the Server

- Press `Ctrl+C` in the terminal to stop Jekyll.

## 9. Cleaning Up

- To remove installed gems: `rm -rf vendor/bundle`
- To reset the site: `git clean -fdx`

---

**For more help:**
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Minima Theme](https://github.com/jekyll/minima)
- Ask in the project repository or contact the maintainer.
