# DebugLogListener

The *DebugLogListener* is the best debugging tool there is during development. It shows you insight in your application in the output window of Visual Studio, even from messages generated by Catel. To use it, use this:

```
#if DEBUG
LogManager.AddDebugListener();
#endif
```