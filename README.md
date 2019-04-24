coyim-pkgsrc
============

NetBSD pkgsrc script for CoyIM.

You can find CoyIM [here][1]

Installation
------------

Copy `chat/coyim` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any package.

`$ cd /usr/pkgsrc/chat/coyim`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above example.

Credits
-------

* The CoyIM is developed and maintained by the [CoyIM Team][3]
* Thanks to `@ppaeps` for a machine to do and test the package development.
* Thanks to `@claucece` for improving the documentation and providing a proper
  `MAINTAINER` mail.
* Thanks to `leot@` and `@coypoop` for reviewing the package in detail.
* This work has been partially sponsored by [CAD][4]

License
-------

BSD 2-clause. See LICENSE.

[1]: https://coy.im/
[2]: https://github.com/coyim/coyim
[3]: https://github.com/orgs/coyim/people
[4]: https://autonomia.digital/
