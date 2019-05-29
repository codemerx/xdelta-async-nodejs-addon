Asynchronous native addon for Node.js that allows generating and applying diffs/patches in VCDIFF format using the [xdelta](https://github.com/jmacd/xdelta) algorithm.

# Usage

The repo could be imported as npm package by adding 

```
"dependencies":  {
  ...
  "xdelta": "git://github.com/ably/xdelta-async-nodejs-addon.git",
  ...
}
```
to your package.json.

# Caveats

The build infrastructure of the addon currently depends on tools that are Mac and Linux specific. Consequently, an installation on Windows will not be possible at this time.


# License

Copyright (c) 2019 Ably Real-time Ltd, Licensed under the Apache License, Version 2.0.  Refer to [LICENSE](LICENSE) for the license terms.
