heroku-buildpack-xmp
====================

A Heroku buildpack that installs XMP Toolkit SDK on the **Cedar-14** stack.  
The version currently installed is CC-2014.12 (http://www.adobe.com/devnet/xmp.html).

Usage
-----

Simply add this Git repo to your `.buildpacks` file and set your Heroku config var `BUILDPACK_URL` to `https://github.com/mojodna/heroku-buildpack-multi.git#build-env`.
