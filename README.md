Orko will be a document management system (DMS) for private use.

This is a NodeJS learning project.

The goal is achieved when it can store PDFs from our scanner and emails from our mail server.

From a software development view I want to establish a code base that follows my "Stable Pluggable Core" concept.

This means that the core system provides an API that can be used to extend the core functionality without understanding the inner workings. This is conceptually a plugin system but with the emphasis on being able to extend the core without the possibility to break the fundamental guarantees of the core API and thus lowering the bar to extend the system.

Maybe all that will not work out, but maybe it will :-)