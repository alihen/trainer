# xcode_log_parser

Because JUnit can actually be parsed

## Installation

```
git clone https://github.com/KrauseFx/xcode_log_parser
cd xcode_log_parser
bundle install
rake install
```

## Usage

### Run tests

```
cd [project]
scan --derived_data_path "output"
```

### Convert the plist files to junit

```
xcode_log_parser
```

### Use the fastlane plugin

[More information](https://github.com/KrauseFx/xcode_log_parser/tree/master/fastlane-plugin-xcode_log_parser)
