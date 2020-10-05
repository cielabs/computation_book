# TidyBlocks

<div>
    <script src="../dist/tidyblocks.js"></script>
    <link rel="stylesheet" href="../dist/css/base.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap"/>
    <script>
        let ui = null
        window.onload = () => {
        TidyBlocksUI = tidyblocks.setup('en', 'root', false)
        }
    </script>
    <!-- UI goes here -->
    <div id="root"></div>
</div>