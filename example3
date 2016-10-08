var casper = require('casper').create();

casper.start('http://www.conservation.ca.gov/cgs');

casper.then(function() {
    this.echo(this.getTitle());
});

casper.thenOpen('http://www.reuters.com/', function() {
    this.echo(this.getTitle());
});

casper.run();
