# localhub

Centralize your files in a unique web interface

# Usage

## Static server

Having a `~/.localhub.json`

    {
      "foo": "~/foo",
      "bar: "/etc/foo"
    }

You could access to:

*   `~/foo/file` from `localhost/foo/file`
*   `/etc/foo/file` from `localhost/bar/file`

# Install

    $ npm install -g localhub
