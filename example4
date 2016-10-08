var casper = require('casper').create();

casper.start('http://google.com/', function() {
   this.waitForSelector('form[action="/search"]');
});

casper.then(function() {
   this.fill('form[action="/search"]', { q: 'kittens' }, true);
});

casper.then(function() {
    this.echo(this.getHTML());
});

casper.run();
