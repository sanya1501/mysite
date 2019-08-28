9:13:08 AM: Build ready to start
9:13:10 AM: build-image version: 9e0f207a27642d0115b1ca97cd5e8cebbe492f63
9:13:10 AM: build-image tag: v3.3.2
9:13:10 AM: buildbot version: f71b4aa1b1ebc2bff806e48691024e0ab383dc02
9:13:10 AM: Fetching cached dependencies
9:13:10 AM: Failed to fetch cache, continuing with build
9:13:10 AM: Starting to prepare the repo for build
9:13:11 AM: No cached dependencies found. Cloning fresh repo
9:13:11 AM: git clone https://github.com/TenSketch/mysite
9:13:12 AM: Preparing Git Reference refs/heads/master
9:13:12 AM: Found netlify.toml. Overriding site configuration
9:13:12 AM: Starting build script
9:13:12 AM: Installing dependencies
9:13:14 AM: Downloading and installing node v10.16.3...
9:13:14 AM: Downloading https://nodejs.org/dist/v10.16.3/node-v10.16.3-linux-x64.tar.xz...
9:13:14 AM: 
#####                                                                      7.0%
9:13:14 AM: 
######
9:13:14 AM:                          8.9%
9:13:15 AM: 
######################################################                    75.3%
9:13:15 AM: 
######################################################################## 100.0%
9:13:15 AM: Computing checksum with sha256sum
9:13:15 AM: Checksums matched!
9:13:17 AM: Now using node v10.16.3 (npm v6.9.0)
9:13:17 AM: Attempting ruby version 2.6.2, read from environment
9:13:18 AM: Using ruby version 2.6.2
9:13:19 AM: Using PHP version 5.6
9:13:19 AM: Installing Hugo 0.57.2
9:13:20 AM: Hugo Static Site Generator v0.57.2-A849CB2D/extended linux/amd64 BuildDate: 2019-08-17T17:57:54Z
9:13:20 AM: Started restoring cached go cache
9:13:20 AM: Finished restoring cached go cache
9:13:20 AM: unset GOOS;
9:13:20 AM: unset GOARCH;
9:13:20 AM: export GOROOT='/opt/buildhome/.gimme/versions/go1.12.linux.amd64';
9:13:20 AM: export PATH="/opt/buildhome/.gimme/versions/go1.12.linux.amd64/bin:${PATH}";
9:13:20 AM: go version >&2;
9:13:20 AM: export GIMME_ENV='/opt/buildhome/.gimme/env/go1.12.linux.amd64.env';
9:13:20 AM: go version go1.12 linux/amd64
9:13:20 AM: Installing missing commands
9:13:20 AM: Verify run directory
9:13:20 AM: Executing user command: hugo --gc --minify
9:13:20 AM: Error: module "hugo-theme-Tensketch" not found; either add it as a Hugo Module or store it in "/opt/build/repo/themes".: module does not exist
9:13:20 AM: Skipping functions preparation step: no functions directory set
9:13:20 AM: Caching artifacts
9:13:20 AM: Started saving pip cache
9:13:20 AM: Finished saving pip cache
9:13:20 AM: Started saving emacs cask dependencies
9:13:20 AM: Finished saving emacs cask dependencies
9:13:20 AM: Started saving maven dependencies
9:13:20 AM: Finished saving maven dependencies
9:13:20 AM: Started saving boot dependencies
9:13:20 AM: Finished saving boot dependencies
9:13:20 AM: Started saving go dependencies
9:13:20 AM: Finished saving go dependencies
9:13:22 AM: Error running command: Build script returned non-zero exit code: 255
9:13:22 AM: Failing build: Failed to build site
9:13:23 AM: failed during stage 'building site': Build script returned non-zero exit code: 255
9:13:23 AM: Finished processing build request in 12.824013651s
