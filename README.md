# fileUtils
provides a comprehensive set of classes for managing common file formats and archives. It streamlines operations for CSV data (using pandas), ZIP file archiving, JSON file manipulation, and plain text file I/O.

## Key Classes
**CsvManager**: Manages CRUD (Create, Read, Update, Delete) operations on CSV files using the pandas library. It handles file creation on initialization, loading/saving DataFrames, and specific actions like retrieving, modifying, and removing rows based on a key (the first column).

**ZipManager**: Provides utilities for working with ZIP archives, including zipping/unzipping directories, adding/removing individual files from an archive, and listing the contents of a ZIP file.

**JsonManager**: Facilitates loading, saving, and manipulating key-value pairs within JSON files. It includes methods for getting, setting, and removing values, as well as retrieving all keys or values.

**txtManager**: A basic utility for managing plain text files. It handles creating empty files, reading the entire content, reading content line-by-line, and writing/appending text.
