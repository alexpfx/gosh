# gosh

git config --global color.ui always
go install github.com/alexpfx/go_sh/dotfile/cmd/repo@latest
go install github.com/alexpfx/go_sh/dotfile/cmd/cfg@latest
fish_add_path $HOME/go/bin/
repo init --help
cfg --help
