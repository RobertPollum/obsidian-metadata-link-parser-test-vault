# Purpose
This is a sample of my old vault where I had been using both the LocalRSS and ReadItLater plugins.

The plugin that this test vault is for is the Metadata Link Parser plugin, which I am in the process of developing. The plugins goal is to bridge the gap between the two plugins by parsing the metadata from the RSS plugin and running it through the Metadata Link Parser plugin to before potentially using the ReadItLater plugin for scraping the content for my local vault.

Mainly it's because RSS feeds often only feed a small description about the article, and I want to be able to scrape the full article content for my local vault. The ReadItLater plugin is great for this, but it doesn't have the ability to parse the metadata from the RSS plugin.

The goal of this test vault is to provide a sample of how the plugin should work, and to test the plugin against real data versus just unit testing sections.

This test-vault is separate to make it easier to test the plugin without having to worry about the vault files being intermingled with the actual plugin repository.
