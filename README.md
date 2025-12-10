watchman-playground
===================
### Downloads
- https://github.com/facebook/watchman/releases/download/v2025.02.24.00/watchman-v2025.02.24.00-windows.zip

### Documentation
- https://facebook.github.io/watchman/docs/cli-options

### Commands
- `watchman --foreground --log-level 2 watch %cd%\..\msvcp140`
- `watchman-wait %cd%\..\msvcp140 -p '*'`
- `watchman-make -p '**/*.c' '**/*.h' --run my_script.sh`


### Tutorials
- https://blog.csdn.net/gitblog_00041/article/details/153170080
- https://github.com/facebook/watchman/issues/36
- https://developers.facebook.com/blog/post/2021/03/15/eli5-watchman-watching-changes-build-faster/
  
