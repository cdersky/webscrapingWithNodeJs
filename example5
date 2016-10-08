var casper = require('casper').create();

casper.options.viewportSize = {width: 1024, height: 768};

casper.start("http://www.reddit.com/", function() {
  console.log('Opened page with title \"' + this.getTitle() + '"');
    casper.capture("./reddit-home.png");
});

casper.run();
