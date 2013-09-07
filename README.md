# localhub

Centralize your services in a unique namespace

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
