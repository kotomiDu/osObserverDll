# osObserver App run on VS 2019
* run `osObserverDllTest.exe <parameter>`
* Log sample, [\*] refers to the active processor.    
![Log](doc/log.png)
* parameter can be `small`, `big`, `all`, `powerthrottle`.
  - `small` `big` indicates using `setAffinty` API to bind the thread with specific processors.
  -  `powerthrottle` indicates using `PowerThrottling` API to hint the thread running with power saving mode but still schedules by OS.
  - `all` indicates the thread uses processors scheduled by OS.

