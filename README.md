# send2lex

_PHP tool to automatically push mail attachments to LexOffice.de account_

### Information
Do not use your daily-use IMAP account for forwarding!
This script forwards all attachments to lexoffice.de.

### Enterprise Support
if you need any assistence to run this script, contact me under www.gruessung.eu

I'll send you an offer for your company.

### Requirements
* lexoffice.de Account
* dedicated imap account for forwarding files

### Installation

Grab your lexoffice.de API KEY on https://app.lexoffice.de/settings/#/public-api

#### build from source
1. clone git repo   
```git clone https://github.com/gruessung/send2lex.git``` 

2. copy .env.sample and adjust to your settigs
``` mv .env.sample .env```

3. start docker-compose 
``` docker-compose up --build```