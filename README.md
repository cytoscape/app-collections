# app-collections
This is the repository for src, target and poms defining collections of apps. 

### How to update
When individual apps are updated, the version information should be updated in the collection's pom.xml. The version of the collection itself should be bumped: minor for updates, major for additions/removals. Finally, run `build package`, commit and push, and upload the lastest jar to the app store.
