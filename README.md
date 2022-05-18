# Ctester
A small shell script which makes testing single file C programs easier, faster and more readable too!

<img src="https://img.shields.io/badge/Tools-experimenting-blueviolet" />

## Info:

### Platforms:

 🍏 <img src="https://img.shields.io/badge/MacOs-working-brightgreen" />


 🐧 <img src="https://img.shields.io/badge/Linux-working-brightgreen" />

### Enviroment:

 🖥️ <img src="https://img.shields.io/badge/C-gcc-blueviolet" />

### Output file:

 📄 output

## Usage:

Insert the file into the folder containing your C source files, then launch it inside your terminal with   

    ./ctester.sh

You'll get prompted with a list of files



Choose the corresponding number and the script will automatically compile and launch your code

### Flags:

 - #### Optional:
    
    * `--a arg0 arg1 arg...`: add arguments to the execution of the compiled file
    
    * `--d max_depth`: sets maximum depth for find search, default is 1
    
    * `--o option`: sets the option to choose in advance, useful when running the tester multiple times on the same file
    
    * `--f flag0 flag1 flag...`: adds flags to the gcc command, it doesn't support flags which start with "--"
    
### Consider adding it to your $PATH so you can run it whitout having to move the scipt everytime!
