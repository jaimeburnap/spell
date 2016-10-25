# spell
Super naive php spell checker based on Peter Norvig's python code (http://norvig.com/spell-correct.html).

I wrote this a very long time ago, right around the time the article came out, so it's not the best code in the world. I have included a new version of the dictionary because I couldn't find the one I used at the time.

# Usage
Just create the object and call `check()`. Returns the word that fits best.
```php
$spell = new Spell();
$spell->check('speling');

Spell::create()->check('speling');
```
