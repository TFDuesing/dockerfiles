Usage
=====

	$ cd [this directory]
	$ docker build -t [image name] .
	$ docker run --name [container name] -d -p 80:80 [image name]

Then, if you’re using boot2docker:

1. run `boot2docker ip`
2. pop that IP address into a web browser
3. **boom** there’s your website
