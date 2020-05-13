# Notes 

Based from [IndexedDB API lab](https://codelabs.developers.google.com/codelabs/pwa-indexed-db/index.html?index=..%2F..dev-pwa-training#0)

How to create, read, update and delete data in the database
The `getAll` method
How to use cursors to iterate over the data

Exploration using a store of products and owners.

`npm install -g http-server`

`http-server -p 8080 -a localhost -c 0`

UI available at [http://localhost:8080/indexed-db-lab/app/](http://localhost:8080/indexed-db-lab/app/)

test report available at [http://localhost:8080/indexed-db-lab/app/test/test.html](http://localhost:8080/indexed-db-lab/app/test/test.html)

----

## IndexedDB

In this lab you learn the basics of working with the IndexedDB API
using the IndexedDB Promised library. It covers the how to create
object stores and indexes, how to use the CRUD operations, and how
to retrieve all of the data.

### Getting started

Clone the repository and navigate to **indexed-db-lab/app**.

Start a local web server at the app base directory. Then, open your browser and
navigate to the appropriate local host port (for example, http://localhost:8080/).

## License

Copyright 2016 Google Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

This is not an official Google product.
