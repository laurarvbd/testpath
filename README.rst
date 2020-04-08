[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Flaurarvbd%2Ftestpath.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Flaurarvbd%2Ftestpath?ref=badge_shield)

Testpath is a collection of utilities for Python code working with files and commands.

It contains functions to check things on the filesystem, and tools for mocking
system commands and recording calls to those.

`Documentation on ReadTheDocs <https://testpath.readthedocs.io/en/latest/>`_

e.g.::

    import testpath
    testpath.assert_isfile(path)
    
    with testpath.assert_calls('git', ['add', path]):
        function_under_test()


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Flaurarvbd%2Ftestpath.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Flaurarvbd%2Ftestpath?ref=badge_large)