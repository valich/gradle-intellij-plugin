### Tasks

Plugin introduces following tasks

- `patchPluginXml` collects all plugin.xml files in sources and fill since/until build and version attributes
- `prepareSandbox` creates proper structure of plugin, copies patched plugin xml files and fills sandbox directory with all of it
- `buildPlugin` assembles plugin and prepares zip archive for deployment
- `runIde` executes IntelliJ IDEA instance with the plugin you are developing installed in
- `publishPlugin` uploads plugin distribution archive to http://plugins.jetbrains.com

**Available in SNAPSHOT:**

- `verifyPlugin` validates plugin.xml and plugin's structure

