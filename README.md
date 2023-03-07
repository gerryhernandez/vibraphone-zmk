# Vibraphone
Custom keyboard for Gerry Hernandez. Flat version of the Marimba with fewer
keys. Physical design by Cyboard.

I use this as a 34 key keyboard, but the outer thumb buttons can be useful for
gaming, so that's what they do at the moment. I'm not much of a gamer and I
actually have different keyboards I'm working on just for gaming. They have
more keys!

**Quick start if you're on macOS:**
```sh
git clone https://github.com/gerryhernandez/vibaphone-zmk
git submodule init
git submodule update
./flash.sh
```

I don't like to rely on GitHub or Docker for building. It's too slow to
iterate and ends up adding noise to the commit log. I enjoy watching my code
fail to build *quickly*! ;-)
