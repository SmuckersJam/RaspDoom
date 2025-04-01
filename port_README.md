To-Do:

- Update libraries to compile, go from there

The objective is for the game to run on a fresh install of Raspbian without installing any additional dependencies.

Doom uses outdated libraries, particularly X11, which isn't pre-installed by Raspbian. Consequently, I need to refactor the code to use Raspbian's built-in libraries.
