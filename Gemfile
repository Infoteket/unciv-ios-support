source "https://rubygems.org"

# Use the GitHub Pages gem so the repository uses the same versions GitHub Pages
# expects. This avoids the "github-pages gem can't satisfy your Gemfile's
# dependencies" warning when the Pages backend builds your site.
gem "github-pages", "~> 232", group: :jekyll_plugins

# Development / CI tools
group :development do
	# html-proofer is useful in CI to validate generated site for broken links
	gem "html-proofer"
end
