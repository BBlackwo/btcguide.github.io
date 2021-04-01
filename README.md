# UPDATES
If you don't have a 2nd computer to run seed picker on you can download the public key info to a CD/DVD (preferred) or a USB drive. Then import the public seed into spectre that you just saved. 
---
Now repeat the above steps, this time using your real seed phrase. Enter your seed phrase, calculate the 24th word, write down the seed phrase on paper, and export public key info. 

# btcguide.github.io

For regular users, just visit <https://btcguide.github.io/> to see GitHub Pages render this content as a static website.

---

For advanced users, you can host this locally with [jekyll](https://jekyllrb.com/) (setup instructions: [Ubuntu](https://jekyllrb.com/docs/installation/ubuntu/); [macOS](https://jekyllrb.com/docs/installation/macos/)):
```bash
$ bundle exec jekyll serve
```

Then visit: <http://127.0.0.1:4000>

To spell check (takes ~3s):
```bash
$ pyspelling -c .spellcheck.yml 
Spelling check passed :)
```

Notes:
* See `.wordlist.txt` for all the exception words.
* `$ brew install aspell && pip install pyspelling` are needed.
