## Changelog

### 1.1.0
New Features
* Support for Multipart POST request

Updates
* Light weight FetchAPI dependency (in replacement for SuperAgent)

Bug Fixes
* Updated putStream and getStream to work for all sized files
* Added obfuscation for output js file (graph-js-sdk-web.js)
* Updated versions of mocha and chai to 5.2.0 and 4.1.2 to fix security vulnerability in growl (which is a dependency of mocha)
* Running unit test files under types directory
* Compiling ts files

#### 1.0.0
* Added tests for new Graph functionality - Delta query, Extensibility, OneNote, and more.

#### 0.4.0
* Add support for ES5. Make sure to use `graph-js-sdk-web.js` for web apps
* Removed iterator helper method.

#### 0.3.1
* Support for Node.js versions 4 and 5

#### 0.3.0
* Migrated away from typings in client library core and TypeScript sample

#### 0.2.2
* Updated SuperAgent to version ``` 3.3.0 ```

#### 0.2.0
* **Breaking change for existing apps** - Initialize the client library with `MicrosoftGraph.Client.init({...})`. See the updated usage section below for code samples.
* Added response handling tests to simulate Graph calls
* Added type declarations file for core client library, which adds intellisense for chained methods.
