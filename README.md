# Latest NodeJS

##### *Automatically download and install Node.js directly from nodejs.org*

`Latest NodeJS` downloads, validates the shasum, compiles, and installs a Node.js stable version. This includes the node and npm executables.

The script can install the latest stable version of Node.js, or a specific release. New versions override the previously installed version by latest-node.


## Usage

After downloading the `latest-node.sh` script, make it executable by changing the file properties or running from a command prompt:
~~~ bash
	chmod u+x latest-node.sh
~~~

There are three types of installation that `latest-node.sh` can carry. In any of these cases, Node.js becomes available as `node` after installation.

#### 1. Latest available version
To install the latest available version of Node.js, run from a command prompt:
~~~
	latest-node.sh
~~~

#### 2. Specific release
To install a specific release (e.g. v0.12.11), run from a command prompt:
~~~
	latest-node.sh v0.12.11
~~~

#### 3. Latest release of a specfic version
To install the latest release of a specific version (e.g. v0.12), run from a command prompt:
~~~
	latest-node.sh v0.12.x
~~~


## Dependencies

`Latest NodeJS` requires:
* Bash
* Curl
* C and C++ compiler infrastructure required by Node.js: clang or gcc, and clang++ or g++.


## License

MIT license. See the LICENSE file for details. 

