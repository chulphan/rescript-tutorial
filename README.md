# Getting started

```
git clone https://github.com/protoship/rescript-tutorial.git
cd rescript-tutorial
npm install
npm run start
```

Then open VSCode in the same directory:

```
code .
```

Install the [rescript-vscode plugin](https://marketplace.visualstudio.com/items?itemName=chenglou92.rescript-vscode). For this, press ctrl+shift+p (cmd+shift+p in Mac) -> "Install Extensions" -> "rescript-vscode".

Now you're all set to begin the tutorial!

Open the first chapter - `chap_1_immutable.res` and follow the instructions in the file.

As you're editing the code, watch the terminal where you ran `npm run start`. It will show any errors from the ReScript compiler and you will have to refer to it often as you're working through the exercises.

The ReScript compiler compiles the `.res` files gets into `.bs.js` files. For the first chapter, that would be `chap_1_immutable.bs.js`. You should open that file as well in a new window by pressing CTRL+O (CMD+O in Mac) and selecting the correct `.bs.js` file. Keep both `.res` file and `.bs.js` file side-by-side so you can see how the ReScript you write gets compiled to JavaScript in real-time.
