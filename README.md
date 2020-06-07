Testing

Delete these scripts from /test/test.html:

    <script src="test.array.js"></script>
    <script src="test.object.js"></script>
    <script src="test.xhr.js"></script>


Use Chai assertion library for mocha tests in the browser.

The node assert module wont work, well because we are running this in the browser and not node...