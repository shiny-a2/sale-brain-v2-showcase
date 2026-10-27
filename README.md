# Sales assistant proxy service

A shared assistant endpoint needs to keep upstream credentials on the server and distinguish client access from administrator access. This service baseline provides a proxy with client tokens, quotas and separate administration.

The reviewed local implementation includes request limits, configurable access restrictions and a management interface. Its source is now preserved privately without client records, environment secrets or installed dependency directories. The archive is a source baseline, not evidence of the version currently running on a server.

JavaScript syntax checks and a secret scan passed. No live provider request, customer conversation, account mutation or production deployment was used as a test. End-to-end runtime validation remains separate from this publication.

The public repository contains only this description. Provider credentials and private implementation files are not included.
