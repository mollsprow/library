# mollsprow's library site

## Development reloading

1. Have latest [Node](https://nodejs.org/en/download/prebuilt-installer/current) installed.
2. Run the following to globally install the `reload` CLI tool:

    ```shell
    npm install -g reload
    ```

3. Navigate to the [`site/`](site/) directory, then run the following to open the page in the browser:

    ```shell
    cd site
    reload -b
    ```

Your browser will open with the site launched as `http://localhost:8080/`. Any change to files within the directory will automatically cause a page refresh in the browser, so you can view changes live as you write them.

Keep the browser open on the side as you hack away. 🙂

To stop the process, in the terminal where `reload` was started, hit `Ctrl-C`.
