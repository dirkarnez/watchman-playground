# watchman-playground
watchman --foreground --log-level 2 watch %cd%\..\msvcp140
watchman-wait %cd%\..\msvcp140 -p '*'
