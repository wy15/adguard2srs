# AdGuard to SRS Converter

This repository uses GitHub Actions to automatically convert AdGuard filter lists to sing-box rule-set format (.srs) daily.

The workflow downloads the latest filter_29.txt from AdGuard's Hostlists Registry and converts it to adguard-cn.srs using sing-box.

## Files

- `adguard-cn.srs`: The generated sing-box rule-set file
- `.github/workflows/convert-adguard.yml`: The GitHub Actions workflow

## License

MIT License