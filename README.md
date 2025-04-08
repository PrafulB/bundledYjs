# bundledYjs
~~Bundles several yjs packages in a single module in order to avoid "Yjs was already imported" problems. Inspired from @rozek/yjs-bundle but only bundles the `y-webrtc` provider and the `y-protocols` encoding protocols library.~~

Modifies the Y-WebRTC provider and the awareness protocol to not depend on the default Y.js import. These dependencies can now be imported individually alongside Y.js without requiring bundling and without incurring the "Yjs was already imported" issue. Importing the non-bundled dependencies also helps in debugging on the web. 

For dev purposes only.

