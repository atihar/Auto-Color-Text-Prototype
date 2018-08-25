<html>
    <head>
        <title>Document</title>
        <style>
                
                #example {
                    justify-items:center;
                    align-items: center;
                    padding: 20%;
                    padding-left: 24%;
                    font-size: 3rem;
                }
                .Txt{
                    padding: 4%;
                }
               
        </style>

    </head>
    <body>
        <div class="row area">
        <input type="color" value="#ff0000"/>
        <div id="example">Smart Text? Lol! we made it</div>

        <!-- we have a run a on browser script for brain .js -->
        <script src="https://unpkg.com/brain.js@1.2.6/browser.min.js"></script>
        <script>
            // its the function to change hex value to rgb. You will find it available in stackoverflow :p
        function hexToRgb(hex) {
                var result = /^#?([a-f\d]{2})([a-f\d]{2})([a-f\d]{2})$/i.exec(hex);
                return result ? {
                    r: parseInt(result[1], 16)/100,
                    g: parseInt(result[2], 16)/100,
                    b: parseInt(result[3], 16)/100
                } : null;
            }
        </script>
        <script>
            // I have tried to implement it using node.js . After that I have directly wrote it into html using js dom
            // we have called brain.js using api in the above

            const input = document.querySelector("input");
            const example = document.querySelector("#example");

            input.addEventListener("change", (e) => {
                const rgb = hexToRgb(e.target.value);
                const network = new brain.NeuralNetwork()
                console.log(rgb)
                // this is the dataset model 
                network.train([
                    { input: { r: 0.62, g: 0.72, b: 0.88 }, output: { light: 1 } },
                    { input: { r: 0.1, g: 0.84, b: 0.72 }, output: { light: 1 } },
                    { input: { r: 0.33, g: 0.24, b: 0.29 }, output: { dark: 1 } },
                    { input: { r: 0.74, g: 0.78, b: 0.86 }, output: { light: 1 } },
                    { input: { r: 0.31, g: 0.35, b: 0.41 }, output: { dark: 1 } },
                    { input: { r: 1.06, g: 1.49, b: 1.43 }, output: { dark: 1 } },
                    { input: { r: 2.36, g: 2.55, b: 2.55 }, output: { light: 1}},
                    { input: { r: 0.9, g: 1.58, b: 1.56 }, output: { dark: 1 } },
                    { input: { r: 1.62, g: 1.08, b: 0.94 }, output: { dark: 1 } },
                    { input: {r: 0.44, g: 0.34, b: 2.21}, output: { dark: 1 } },
                    { input: { r: 0.01, g: 2.54, b: 2.22 }, output: { light: 1 } },
                    { input: { r: 0.62, g: 1.93, b: 0.71 }, output: { dark: 1 } },                  

                    
                ])

                const result = brain.likely( rgb, network )
                console.log(result);
                // here is what I said to style according to dark and light color
                // that's it
                example.style.background = e.target.value
                example.style.color = result === "dark" ? "white" : "black"
            })
        </script>
        </div>
        <div class="row Txt">
            <p><b>Test Project Name:</b> Auto Color Text Prototype <br><br>
                <b>Instructions:</b>Select the color point. Its gonna change the text color to white* when you select any dark background and vice versa. Isn't Fun?<br><br>
                <b>About:</b>This is an example of implementation of machine learning using javascript. You can use brain.js in backend with node.js. Many problem can 
                be solved using this type of programming which can't be done using traditional programming methods<br><br>
                <b>Technical Description:</b> We have taken some RGB value to train the model of the neural network and using that dataset we 
                trained the machine what may be the dark color or light color.<br>
                To change the hex value to RGB value we created a separate function here.<br><br>
                <b>Credit:</b> Brain.js<br>
                <b>Project Author:</b> Atihar Hossan Mahir<br>
                Follow me <a href="https://atiharhossanmahir.com">@mahir890</a>
            </p>
        </div>
    </body>
</html>
