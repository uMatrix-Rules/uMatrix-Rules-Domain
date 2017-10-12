## Vrooboo! Wabbo!!

Here is a summation of all relevant knowledge you should have learned before using the ruleset.

### FAQs

1. What are principles on enabling third-party elements?
    The first prioirty  is to be sure most site function for normal browsing is working as how it is expected. The more elements is blocked despite that, the better.
1. It this enough (any other privacy tools recommened)?
    It is definitely not enough, some third-party elements contain both normal site facilities and also tracking scripts. Here are some others helpful:
    - [CanvasBlocker](https://github.com/kkapsner/CanvasBlocker)
    - [Cookie-AutoDelete](https://github.com/Cookie-AutoDelete/Cookie-AutoDelete)
    - [Decentraleyes](https://decentraleyes.org/)
    - [HTTPS Everywhere](https://www.eff.org/https-everywhere)
    - [Neat URL](http://hugsmile.eu/)
    - [uBlock Origin](https://github.com/gorhill/uBlock)
1. How can I donate?
    No any will to accept yet.
## Gnar gada! - USAGE

1. Save file from [this link](https://github.com/Rictusempra/uMatrix-Rules/raw/master/rules.txt) into any local directory or directly open it in your browser & copy all contents
2. open your uMatrix dashboard
3. navigate to `My rules` tab
4. click `Import from file...` and pick the file you just downloaded or click `Edit` and paste them
5. edit as your like or click `Save`, and then `Commit`

## Shubbanuffa - BEFORE USING

- I can only ensure most site functions are workable. Use at your own risk.
- If you are expecting my investigation on any specific site, pls open a [new issue](https://github.com/Rictusempra/uMatrix-Rules/issues/new):
    - give a specific URL
    - point out your uMatrix version & broswer version
    - attach your own rules and, if differ from default, your preferences
- Here are service inavailablity things that won't be fixed:
    -  from contents blocked by any built-in subscriptions
    - caused by certain preferences outside of rule sets or of uMatrix itself
    - if a site:
        -  is using cert from any untrusted CA
        - containing **mostly only** pornographic content
        - reported as a deceptive site
        - is a private blog site that is not hosted on public serivce
    - relevant with any plugin, such as Adobe Flash
    - other issues you should have learnt from uMatrix [README](https://github.com/gorhill/uMatrix/blob/master/README.md) or [wiki](https://github.com/gorhill/uMatrix/wiki)

---

## Ovagarava - T.O.C.

- [Blacklist Mode](Blacklist-Mode.md)
- [Contributing](Contributing.md)
- [Cookies Control](Cookies-Control.md)
- [uMatrix Friendly Sites](uMatrix-Friendly-Sites.md)
- [User Agent Spoofing](User-Agent-Spoofing.md)
- Third Party Iframe
    - [Google Service](/Google-Services.md)
    - [Video Iframe Examples](/Video-Iframe-Examples.md)

### Reeshoova! - LICENSE
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>
Except where otherwise noted, all content in this repository is licensed under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0 International License</a>
