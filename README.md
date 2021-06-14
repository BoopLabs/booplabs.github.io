# Boop! Labs Website: Maintence Information
This site uses MEML developer tools (MLD). To use them run the command `npm i -g mld`! Once done, the `/src/` directory contains all MEML code. Once ready to compile a test build run `mld build .` in the project's root directory. If you are satisfied with a build, run `mv ./build/* ./public/.`.

- The `/public` directory has all public code that displays the website.
- The `/src` directory has all of the MEML code. If you have an error, contact `<kai@fivnex.co>`.
- The `/build` directory contains all builds by the MLD compiler, unless you run `mld build --out <directory>`. This directory is ignored by Git.

> DO NOT DO DEVELOPMENT IN THE `/build` OR `/public` DIRECTORIES. ALL SITE SOURCE CODE IS DONE VIA MEML.