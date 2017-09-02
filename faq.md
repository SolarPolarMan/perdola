# Frequently Asked Questions
----

**Q:** What is this and why should I use it?:

**A:** This is a complete redesign of the traditional password generator/storage system. Instead of relying on a hard drive to not to fail, or that backup you keep forgetting to make, Perdola makes a password based on your master password and the application you want a password for. This generated password will be the same every time, no matter what device you're on. You can then copy this and paste it into the app you want to log into.



**Q:** How do I know you're not looking at my passwords?:

**A:** When you type, your computer takes the app name and your master password and using them makes a new password. Nothing is ever sent across the internet, other than the code for the website itself. If you really want, you can [download the files](https://github.com/ChildishGiant/perdola) for the website, smash your router and run Perdola offline (Not that I'd recommend smashing your router.)


<a name="remake">**Q:** Why did you remake an existing product?:</a>

**A:** I've openly acknowledged that Perdola is based off the concept of "[Master Password](https://masterpasswordapp.com/)" but why would I spend all this time re-making a working piece of software? The answer is simple: *I don't like how master password works.* It has many different offshoots that all look different. It takes 6 variables to make a password and 30 seconds to load (Yes, I timed it.). It makes everything harder than it should be. And that was my motivation to make Perdola. I absolutely love the concept of secure passwords without storing them but hate the current solutions.

**Q:** My favourite app isn't on Perdola!!!!1!:

**A:** That's not a question but there is something you can do about it! Submit an issue [on github](https://github.com/ChildishGiant/perdola/issues/new) specifying the site you want added and I'll do my best to add it.

<style
  type="text/css">
  @import url(https://fonts.googleapis.com/css?family=Open+Sans);

  body {
    color: #444;
    font-family: 'Open Sans', sans-serif;
    max-width: 75%;
    text-align: center;
    margin:auto;
    margin-top:2em;
  }

  a[href],
  a[href]:visited {
    color: #3498db;
  }

  a[href]:hover,
  a[href]:focus,
  a[href]:active {
    color: #2980b9;
  }
  p{
    padding: 10px 1em;
  }
  em{
    font-style: normal;
    background-color: #ffff87;
    box-shadow:3px 0 0 #ffff87, -3px 0 0 #ffff87;

  }

  a:target {
    text-decoration: underline;
    font-weight: bold;
  }
</style>