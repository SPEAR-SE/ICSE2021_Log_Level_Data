# ICSE2021_Log_Level_Data

This is the repository containing the data for paper "DeepLV: Suggesting Log Levels Using Ordinal Based Neural Networks" at ICSE2021 Technical Track.

- `AST.zip` contains the AST nodes with their related information extracted from the studied systems. For each AST node:
    - `method` indicates in which the method of this AST node locate
    - `type` indicates the type of this AST node
    - `name` shows the contents of this AST node
    - `begin` shows the begin line of this AST node in its class file
    - `end` shows the end line of this AST node in its class file

- `logging_statements.zip` contains the logging statements with their related information extracted from the studied systems. For each line of logging statement:
    - `logcall` represents for the logging library that a logging statement invokes
    - `parameter` lists all the parameters of this logging statement (including static message and dynamic variables)
    - `constant` shows the static message of a logging statement
    - `level` shows the verbosity level of this logging statement
    - `callsite` represents for the class and method of that this logging statement locates in
    - `line` shows the line number that this logging statement locates at

- `manual_study.xlsx` contains the detailed results of our manual study in Section-II

- `log_level_code.rar` contains the code related to this study
