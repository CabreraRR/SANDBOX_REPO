cask_args appdir: "/Applications"
tap "caskroom/cask"
tap "telemachus/brew", "https://telemachus@bitbucket.org/telemachus/brew.git"
brew "imagemagick"
brew "mysql", restart_service: true, conflicts_with: ["homebrew/versions/mysql56"]
brew "emacs", args: ["with-cocoa", "with-gnutls"]
cask "google-chrome"
cask "java" unless system "/usr/libexec/java_home --failfast"
cask "firefox", args: { appdir: "~/my-apps/Applications" }