The location of static files. I generally store static files in a separate repo because the code and static files tend to be served from different places around 90% of the time. Then I usually relative symlink each app's static folder to this folder. This way you do not store duplicate static files in your code repo, but you can still run your app easily in a development environment.