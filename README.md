# ieeevis.org

Hi!  This is the Jekyll version of the [IEEE VIS website](http://ieeevis.org).

The `vis2025` branch (the page you're currently viewing) is the current year's website.

To edit files in other years, check out the other `vis*` branches.  Click the below links to teleport:
- [vis2023](https://github.com/ieee-vgtc/ieeevis.org/tree/vis2023) - the 2023 redesign
- [vis2022](https://github.com/ieee-vgtc/ieeevis.org/tree/vis2022) - the 2022 redesign
- [vis2021](https://github.com/ieee-vgtc/ieeevis.org/tree/vis2021) - the 2021 redesign
- [vis2020](https://github.com/ieee-vgtc/ieeevis.org/tree/vis2020) - the 2020 redesign
- [vis2019](https://github.com/ieee-vgtc/ieeevis.org/tree/vis2019) - the 2019 redesign
- [master](https://github.com/ieee-vgtc/ieeevis.org/tree/master) - the original website design (years 2018 and previous)

## Contributing

If you're contributing content, but not administrating the website itself, you will want to follow the [contributor's guide](http://ieeevis.org/year/2025/info/contributing).

## Building

**Automatic building**: The [.github/workflows/staging.yml](/.github/workflows/staging.yml) file contains a GitHub Actions workflow for deploying the site.

![](https://github.com/ieee-vgtc/ieeevis.org/workflows/build%20staging/badge.svg)

**To build locally**, run `bundle exec jekyll serve -d ./_site -b '/' && npm run-script start`.  You may need to break these commands apart and run `npm run-script start` in a separate console.

You may need to install [npm/node](https://nodejs.org) and Ruby (we recommend [rbenv](https://github.com/rbenv/rbenv#readme) and using [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) if not on a UNIX-like system), and install the bundler gem (`gem install bundler`).   Once the package managers are installed, run them both to install dependencies (`npm install` and `bundle`), and then build the site `npm run build`.

