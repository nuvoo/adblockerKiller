Ad Blocker Killer
================

Stop people accessing a website, if they are using ad blocker.

Usage
-----

```$(element).adBlockKiller({
          removeElementContent: 'html', // html element to delete and replace with stopMessage
          stopMessage: 'Your\'re seeing this message because you have an ad blocker enabled. Please consider turning off your ad blocker on our site. Our adverts are non-intrusive and help us keep the website running without cost. Please <a href="http://removeadblock.com/">click here</a> to find out why you should remove adblock.', // message that displays if user is using adblocker
          redirectUrl: null, // url to redirect to
          trollPopups: false, // turn off/ on infinite pop ups
          trollPopupsMessage: 'stop using adblocker' // message that is displayed in pop up
});

It is recommend to attach adBlockKiller to the body object
