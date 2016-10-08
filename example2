var casper = require('casper').create();

casper.start('http://www.conservation.ca.gov/cgs');

casper.then(function() {
    this.echo(this.getHTML());
});

casper.run();
