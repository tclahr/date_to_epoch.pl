# 🕒 Perl Script: Convert ISO Date to Unix Epoch Timestamp

[![GitHub License](https://img.shields.io/github/license/tclahr/date_to_epoch.pl?color=blue)](https://github.com/tclahr/date_to_epoch.pl/blob/main/LICENSE)

## Overview

`date_to_epoch.pl` is a simple, lightweight **Perl script** that converts a date in ISO 8601 format (`YYYY-MM-DD`) into a **Unix epoch timestamp** (seconds since January 1, 1970, UTC).

Whether you're working with logs, scheduling tasks, or processing time-based data, this script provides a fast and reliable way to convert human-readable dates into machine-friendly epoch format using native Perl.

## 🔍 Features

- Convert `YYYY-MM-DD` dates to epoch time
- Written in pure Perl – no external dependencies

## 🚀 Usage

```bash
perl date_to_epoch.pl YYYY-MM-DD
```

### Example

```bash
$ perl date_to_epoch.pl 2024-12-25
1735084800
```

## 🛠️ Requirements

- Perl 5 (standard on most Unix-like systems)
- No additional modules required beyond `Time::Local` (core Perl module)

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve the script, add new features, or support other date formats.

## 📝 License

This project is licensed under the [Apache License 2.0](LICENSE).
