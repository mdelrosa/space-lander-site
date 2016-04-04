# space-lander-site

[Website](elecanisms.olin.edu/2016/lander) for Space Origin: X Elecanisms team.

## Serving Locally

While working on editing the site, you should serve the site locally on your machine before pushing changes to the live site. To serve the static content locally on your machine, you can use the [node-static](https://www.npmjs.com/package/node-static) package. To do this:

1. Install the static package:

    ```
    npm install -g node-static
    ```

2. Navigate to the local directory containing the static content.
3. Run:
	
	```
	static
	```
    You should be able to navigate to localhost:8080 in your browser and see the index.html file.

## Updating the Site

To update the site, you need to navigate to the proper directory on linwebprod.olin.edu.

1. SSH into the linwebprod.olin.edu machine:

    ```
    ssh your-olin-account-here@linwebprod.olin.edu
    cd /var/www/virtual/elecanisms.olin.edu/html/2016/lander
    ```

2. Pull your changes from Github (this repo is already initilized in the directory)

     ```
     git pull origin master
     ```
