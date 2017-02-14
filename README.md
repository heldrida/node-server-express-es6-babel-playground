
	https://github.com/thejameskyle/babel-handbook/blob/master/translations/en/user-handbook.md#toc-babel-register

	babel-register:

	The next most common method of running Babel is through babel-register. This option will allow you to run Babel just by requiring files, which may integrate with your setup better.

	Note that this is not meant for production use. It's considered bad practice to deploy code that gets compiled this way. It is far better to compile ahead of time before deploying. However this works quite well for build scripts or other things that you run locally.