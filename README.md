#Antivcode

#Usage

###examples:
First you should let the program study and generate attribute code database.

To get help information:

```
>> decode -h
Or
>> decode --help
```

To study by filenames from ./folder and create a new database named "db" in ./database:

```
>> decode -syn -d ./folder/ -b ./database/db
Or
>> decode -s -y -n -d ./folder/ -b ./database/db
```

To study sigle file and append to database by default(./db):

```
>> decode -s -f simples/studied.jpg
```

if you want to see binaryzated image, just add -v option.

When finish studying, you can run a test or recognition.

To test a single file:

```
>> decode -t -f simples/tested.jpg
```

To test a series of images:

```
>> decode -t -d test/
```
Note: test procedure require that file named with a right name.

To recognite a single file:

```
>> decode -f simples/recognited.jpg
```

To recognite a series of files:

```
>> decode -d simples/
```
