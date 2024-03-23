## Commands to Build and Serve Webpages

### bundle exec jekyll build  
`bundle exec`: This makes sure that the command uses the correct versions of the tools and libraries your project needs.

`jekyll build`: This tells Jekyll, the tool for building websites, to take all your website's pieces (like text files and templates) and put them together to make the actual website you can view in a web browser.


### bundle exec jekyll serve  
`bundle exec jekyll serve` combines both the execution context management provided by `bundle exec` and the Jekyll command to build your site and serve it locally for testing and development purposes. It's a convenient way to ensure that the correct gem versions are used while running Jekyll commands.