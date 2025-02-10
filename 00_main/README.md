# Sample project

You can use the following command to create a simplest esp-idf project, taking the main project as an example.

```
idf.py create-project main
```

Enter the corresponding project directory

```
cd main
```

Project file list:

```
├── CMakeLists.txt
└── main
    ├── CMakeLists.txt
    └── main.c
```


Set the target ESP chip model: esp32s3

```
idf.py set-target esp32s3
```



Open the configuration menu

```
idf.py menuconfig
```



Compile the firmware

```
idf.py build
```



Burn the firmware and open the serial port assistant

```
idf.py flash monitor
```





