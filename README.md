# mlx-reader
Simple python script that extracts contents of .mlx files and writes them to .m file.
## Usage
You just run the program with the path to the mlx file as argument. If you want you can also specify the path of the output m file, like this:

`
mlxreader path/to/file.mlx /output/file.m 
`
## WIP
The script will only recognize code and headers. To add different parts of a mlx script is not hard to do (just modify an if statment) but I don't need them for now. If you implement something please send a pull request.
