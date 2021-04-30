# web-assembly-trial

There are many options to generate a web-assembly code using multiple languages.
Rust, Golang, Assembly-script, C with Emscipten
When we compile the code to web-assembly target, it generates `.wasm` file.
For each source language there is some glue code is added to the generated web-assembly code.
Smaller the glue code, lesser the `.wasm` file size.
Here we will create simple project to `Calculates the n-th Fibonacci number` in each possible source language to see which one genertaes the lightest `.wasm` file. 
