# Confluence Plugin

The moveworks_search plugin for Confluence Server or Data Center editions provides users and group permission for a given space id. The API also returns Instance Info (version number) and Plugin Info (version number).

## Installation

Releases are hosted on [GitHub](https://github.com/moveworks/confluence-plugin/releases). To install:
1. Go to `Manage apps` in Confluence's administration settings.
1. Click `Upload app`
1. Enter the URL to the `JAR` file from the release page.

## Implementation

There is 1 API endpoint - /rest/api/{version}/space/{SPACE_ID}/permission

