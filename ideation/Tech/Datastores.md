At least four types of datastore will be required for this application:
- **Relational database:** The primary source of truth for most user generated content, ingested data sets, and site configuration.
- **ElasticSearch:** A searchable index of user posts and comments, businesses, events, and more. Effectively a structured cache of data sourced from the relational database. Search indices can be rebuilt on demand to add features, optimize queries, or recover from loss.
- **In-Memory Cache:** Some kind of caching mechanism like Redis can be used to store user sessions, computed values, and documents that are read more often than they are written. The more we can cache, the faster and cheaper the platform will be to run
- **Static File Store:** All modern web applications need a place to serve code and assets from. Uploaded images can also be stored here. Some uploaded content will require authorization to access, but most can be made publicly available.

All datastores need to emit [runtime metrics](<Runtime Metrics>). The relational database and static file store must be subject to regularly scheduled backups.