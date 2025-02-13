# Bulk Kindle Library Tools


This is a fork of [BulkKindleDownloader](https://github.com/Jedi425/BulkKindleUSBDownloader/), which is a fork of [bOOkp](https://github.com/sghctoma/bOOkp).

Download & Transfer option is being deprecated, but I hope to modify it to:

* work with other browsers other than Chrome
* download metadata for all books
* update all books with updates
* send some set of books to a particualar device registered to the Amazon account in question

Intial version does not do any of these things.

## Usage

```
usage: bookp.py [-h] [--verbose] [--showbrowser] --email EMAIL
                [--password PASSWORD] [--outputdir OUTPUTDIR] [--proxy PROXY]
                [--asin [ASIN [ASIN ...]]] [--logfile FILENAME]

Amazon e-book downloader.

optional arguments:
  -h, --help            show this help message and exit
  --verbose             show info messages
  --showbrowser         display browser while creating session.
  --email EMAIL         Amazon account e-mail address
  --password PASSWORD   Amazon account password
  --outputdir OUTPUTDIR
                        download directory (default: books)
  --proxy PROXY         HTTP proxy server
  --asin [ASIN [ASIN ...]]
                        list of ASINs to download
  --logfile FILENAME    log output to a file
```

## Requirements

* [Python 3.x](https://www.python.org)
* [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads)
* the following Python modules:
  * [requests](https://pypi.org/project/requests/)
  * [PyVirtualDisplay](https://pypi.org/project/PyVirtualDisplay/)
  * [selenium](https://pypi.org/project/selenium/)
