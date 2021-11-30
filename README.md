# demo
build targets :
`bazel build //...`

execute binary :
`bazel run //:demo` 

quiet run :
`bazel run --ui_event_filters=-info,-stdout,-stderr --noshow_progress //:demo` 
