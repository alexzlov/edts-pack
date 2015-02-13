# edts-pack

EDTS (https://github.com/tjarvstrand/edts) pack for emacs-live (https://github.com/overtone/emacs-live).

Install https://github.com/vimalearnest/erlang-pack first.
Then clone edts-pack to ~/.live-packs and add following to your ~/.emacs-live.el:

(live-apend-packs '(~/.live-packs/erlang-pack/ ~/.live-packs/edts-pack)).

You'll also need to set edts-inhibit-package-check as t in 
  ~/.live-packs/edts-pack/lib/edts/edts-start.el
to supress the warning message.
