(package "electric-operator" "0.1" "Automatically add spaces around operators")

(files "electric-operator.el")

;; Tell Cask to add package information to this file (so that we can have a
;; single file package).
(package-file "electric-operator.el")

(source melpa-stable)

(development
 (depends-on "ecukes")
 (depends-on "espuds")

 ;; For testing, not available on melpa stable so pull from github directly
 (depends-on "rust-mode" :git "https://github.com/rust-lang/rust-mode.git")

 ;; For testing
 (depends-on "ess")
 )
