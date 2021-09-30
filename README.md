# CORAL Project installation

This will explain what to do to install and run the CORAL-Project Website locally for testing purposes

### installation

install bundler first:

    root > apt install bundler

then clone the repo

    user > git clone <<REPO>>

then run:

    user > bundler install

### run test server

to test the site locally, simply run:

    user > bundle exec jekyll serve

play with the website as you want by going here:

    localhost:4000

done, have fun!

### Troubleshooting

Please verify the `bundle install` or use `bundle update` for updates.

To stop the running server, go back to the terminal that was running the local server in the first place and hit `CTRL+C`

