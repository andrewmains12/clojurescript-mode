
A mode for clojurescript which supports using a clojurescript repl (through use of the excellent
lein-cljsbuild.)

The mode derives from clojure-mode, so pretty much everything should be the same as there. The only
exception is that instead of starting inferior-lisp processes in "\*inferior-lisp\*", it starts them in
"\*cljs\*". All repl evaluation functions from clojure mode should work.

This does NOT in any way use SLIME, sadly. 

Assumes you've got both lein and cljsbuild already set up (if not, see https://github.com/emezeske/lein-cljsbuild).

"Forked" from http://marmalade-repo.org/packages/clojurescript-mode (I couldn't find the github page, so I just started hacking on the source from marmalade)