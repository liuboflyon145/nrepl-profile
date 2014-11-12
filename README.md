# nrepl-profile

nREPL support for [thunknyc/profile](http://github.com/thunknyc/profile).

## TODO

* Write a README
* Show folks how to add the right things to their `${HOME}/.lein/profile.clj`. (Basically: add `[thunknyc/nrepl-profile "0.1.0-SNAPSHOT"]` to `:dependencies` and `{:nrepl-middleware [nrepl-profile.core/wrap-profile]}` to `:dependencies` in your `:user` profile.)
* Write a `plugin.clj` file to obviate the need for thinking about contents of bullet point supra.
* Package the elisp and make it accessible from MELPA.

## License

Copyright © 2014 Edwin Watkeys

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
