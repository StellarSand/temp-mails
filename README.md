# temp-mails
A list of many disposable and temporary email address domains.

As of Aug 11, 2023, the [final list](https://github.com/the-weird-aquarian/temp-mails/blob/main/final_list.txt) has 157461 domains.



## Contents
- [How does it work?](#how-does-it-work)
- [Supported OS](#supported-os)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)



## How does it work?
This script retrieves data from multiple sources, combines them, removes duplicates and sorts it to create a final list.

#### Data sources
- [FakeFilter](https://github.com/7c/fakefilter)
- [disposable-email-domains](https://github.com/disposable-email-domains/disposable-email-domains)
- [burner-email-providers](https://github.com/wesbos/burner-email-providers)
- [disposable_email_domains](https://github.com/stopforumspam/disposable_email_domains)
- [MailChecker](https://github.com/FGRibreau/mailchecker)
- [MailCheck.ai](https://www.mailcheck.ai)
- [Some extra domains](https://github.com/the-weird-aquarian/temp-mails/blob/main/extras.txt)



## Supported OS
- GNU/Linux
- Windows
- macOS



## Prerequisites
- [Python3](https://www.python.org/downloads/)
- [BeautifulSoup](https://pypi.org/project/beautifulsoup4/): Install using `pip install beautifulsoup4`
- [requests](https://github.com/psf/requests): Install using `pip install requests`



## Usage
A [final list](https://github.com/the-weird-aquarian/temp-mails/blob/main/final_list.txt) is already included which can be used directly.

To obtain a more updated data, follow these steps:

**1. Clone this repo:**
```
git clone https://github.com/the-weird-aquarian/temp-mails.git
```

**2. Move into the project directory:**
```
cd temp-mails
```

**3. Give executable permissions to the script (Not required for Windows):**
```
chmod +x temp-mails
```

**4. Run the script:**
```
python3 temp-mails
```

NOTE: Due to large dataset while retrieving data from [MailCheck.ai](https://www.mailcheck.ai), the script will intentionally pause frequently to avoid scraping detection.



## Contributing
Pull requests can be submitted [here](https://github.com/the-weird-aquarian/temp-mails/pulls).


## License
This project is licensed under the terms of [MIT license](https://github.com/the-weird-aquarian/temp-mails/blob/main/LICENSE).
