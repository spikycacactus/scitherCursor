How to install:
1. Install hyprcursor
sudo pacman -S hyprcursor

2. Create directory .local/share/icons
mkdir .local/share/icons

3. Add to hyprland config:
exec-once = hyprctl setcursor scytherCursor 32
env = HYPRCURSOR_THEME,scytherCursor
env = HYPRCURSOR_SIZE,32

4. To activate in console:
hyprctl reload
hyprctl setcursor scytherCursor 32
