# gnome-shell-theme

Alter existing /usr/share/gnome-shell/gnome-shell-theme.gresource with Adwaita Night (gnome-backgrounds) background.

glib-compile-resources gnome-shell-theme.gresource.xml
sudo cp /usr/share/gnome-shell/gnome-shell-theme.gresource /usr/share/gnome-shell/gnome-shell-theme.gresource.backup
sudo cp gnome-shell-theme.gresource /usr/share/gnome-shell/
