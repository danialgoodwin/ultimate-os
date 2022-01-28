# Keyboard Shortcuts

Modifier keys:
- 'os' for commands that aren't directed into apps (aka, windows-key or apple-key)
    - Ideas: Control movement/opening/starting of os-level things like windows/apps
- 'app' for commands internal to apps that apps can control (aka, control-key or command-key)
- 'shift' for extra key usages
- 'alt' for alternative key usages

config
  is-disable-system-shortcuts-for-games false

system-command os+space 'Open prompt to send commands to the system, like search and open-app'
system-escape os+esc 'Open prompt for settings, and to shutdown, sleep, restart'
system-help os+/ os+? 'Open system help information, including keyboard shortcuts'
system-toggle-app-focus os+tab
system-move-app-up os+up 'Move app to full-screen, then to top-half, then top-quarter'
system-move-app-right os+right 'Move app to right-half, then the next monitor'
system-move-app-down os+down 'Move app to the bottom-half, then bottom-quarter, then minimized'
system-move-app-left os+left 'Move app to left-half, then the previous monitor'
system-open-1 os+1
system-open-2 os+2
system-open-3 os+3
system-open-4 os+4
system-open-5 os+5
system-open-6 os+6
system-open-7 os+7
system-open-8 os+8
system-open-9 os+9
system-open-calculator os+app+c
system-open-calendar os+app+k
system-open-explorer os+app+e
system-open-mail os+app+m
system-open-notes os+app+n
system-open-social os+app+s 'Open Social app, includes contacts, text, voice, video'

app-close app+q ;; Same as quit
app-copy app+c
app-cut app+x
app-find app+f
app-new app+n
app-open-file app+o
app-paste app+v
app-print command.app-share ;; Same as app-share.
app-redo app+shift+z
app-save app+s
app-save-as app+shift+s
app-select-all app+a
app-share app+p
app-toggle-focus app+tab
app-undo app+z
