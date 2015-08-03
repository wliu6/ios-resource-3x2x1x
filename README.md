# iOS 3x to 2x and 1x

### Description
ios-resource-3x2x1x is a shell script which aim to convert 3x resource to 2x and 1x simply.
<pre>
VERSION: 1.0.0
USAGE: ./ios-resource-3x2x1x.sh srcdir dstdir

DESCRIPTION:
    This script aim to convert 3x to 2x and 1x.

    srcfile - The source path. Must be 3x.
    dstpath - The destination path where the icons generate to.

    This script is depend on ImageMagick. So you must install ImageMagick first
    You can use 'sudo brew install ImageMagick' to install it

AUTHOR:
    Pawpaw<lvyexuwenfa100@126.com>

LICENSE:
    This script follow MIT license.

EXAMPLE:
    ./ios-resource-3x2x1x.sh ~/input ~/output
</pre>

### Usage
1. Install ImageMagick
	
	Before you run this script, please check whether you had install ImageMagick. If you don't have install. Follow this:
	<pre>
	sudo brew install ImageMagick</pre>

2. Clone And Chmod
	<pre>
	git clone https://github.com/smallmuou/ios-resource-3x2x1x
	cd ios-resource-3x2x1x.sh
	chmod 777 ios-resource-3x2x1x.sh.sh
	</pre>
3. Run
	<pre>
StarnetdeMacBook-Pro:ios-icon-generator starnet$ ./ios-resource-3x2x1x.sh ~/Downloads/input ~/Dowload/output
[INFO] mkdir /Users/starnet/Downloads/output/2X ...
[INFO] mkdir /Users/starnet/Downloads/output/1X ...
[INFO] /Users/starnet/Downloads/output/2X/1@2x.jpg ...
[INFO] /Users/starnet/Downloads/output/1X/1.jpg ...
[INFO] /Users/starnet/Downloads/output/2X/2@2x.jpg ...
[INFO] /Users/starnet/Downloads/output/1X/2.jpg ...
[INFO] Done</pre>
PS: You can find out all resource in ~/Download/output directory.
	
### History
* 1.0.0
	* Support convert 3x to 2x and 1x.

### License
This script follow MIT license.

### Contact
If you have any question with using it, you can email to me. My email is: lvyexuwenfa100@126.com