# Exchanges

## Which exchanges does FinTax support?&#x20;

FinTax currently supports the following:&#x20;

Binance, Okx, Bybit, Kraken, CoinSpot, Swyftx, Huobi, Gate.io, Bitfinex, Bitget, Upbit, CoinEx,&#x20;

Crypto.com, OSL, Coinbase. KuCoin, Bitflyer

AscendEX, Bithumb, Bitstamp

CoinList, Copper, dYdX,&#x20;

Fireblocks, Galaxy, Gemini, Indodax, LMAX, MEXC&#x20;

Poloniex



## How to add your Exchange account?

### Binance

1.Open the Binance [Account API ](https://accounts.binance.com/en/login?return\_to=aHR0cHM6Ly93d3cuYmluYW5jZS5jb20vZW4vbXkvc2V0dGluZ3MvYXBpLW1hbmFnZW1lbnQ=)page\
2.Select Create Tax Report API (this is limited to read-only access)\
3.If applicable, enter your two-factor authentication code and email verification code\
4.Copy the API Key and Secret and paste into Fintax

### Kraken

1.Log in to Kraken [Kraken](https://www.kraken.com/)\
2.Click on your name in the upper-right corner of the page and choose Security and then choose API\
3.Select Add key\
4.Enable the following permissions:\
Query funds\
Query closed orders & trades\
Query ledger entries5.Select Generate key\
6.Copy the API Key and Private Key and paste into Fintax

### CoinSpot

1.Open the CoinSpot [API page](https://www.coinspot.com.au/my/api)                                                                                                                                      2.Click the Generate New Api Key button                                                                                                                 3.Enter any name, and select the Read Only API key type                                                                                           4.If applicable, enter your Two Factor Code                                                                                                                5.Confirm the new API key by email                                                                                                                            6.Reveal the API secret, and copy the Key and Secret

### Swyftx

1.Open [Swyftx Manage Keys](https://trade.swyftx.com.au/profile/api/) page                                                                                                                                 2.Click "Generate NEW KEY" button                                                                                                                             3.Enter a label (example: Fintax) and click "NEXT" button                                                                                  4.Select check boxes on: Account.Tax Report, Account.Balance, Account.Read, Address.Read, Orders.Read, Funds.Read and click "NEXT" button                                                                                                          5.Enter Swyftx account password and click "NEXT" button                                                                                    6.Copy API KEY7.On this page paste it in the field and click "Add Account" button

### Huobi

1.Follow the instructions on [how to create a Huobi API key](https://www.htx.com/support/en-us/detail/360000203002)\
2.Copy and paste the API key and secret to Fintax here

### Gate.io

1.Follow the instructions on [how to create API V4 Key](https://support.cointracker.io/hc/en-us/articles/4413049686417-Integrating-Gate-io-with-APIv4-keys)\
2.Copy the Key and Secret

### Bitfinex

1.Open the [Bitfinex API](https://www.bitfinex.com/api) page.                                                                                                                             2.Select Create New Key                                                                                                                                                     3.Keep the default permissions unchanged - all 'Read' permissions enabled.                                                                                                                4.Enter a label for the API key, such as 'FinTax'                                                                                                                         5.Select Generate API key                                                                                                                                           6.If applicable, enter your two-factor authentication code.                                                                    7.Confirm the new API key from the verification email you receive from Bitfinex                                                                                                         8.Copy the API Key and API Key Secret.

### Crypto.com

**NOTE:** These instructions apply to the Crypto.com exchange, please see instructions for the Crypto.com app available to US users here.

&#x20;1.Within the Crypto.com Exchange web app, click your Profile (upper right corner)                                                                                                      2.Select Settings, and then select API Keys                                                                                                                                           3.Select Create a new API key, enter a label such as "FinTax," and enter your 2FA code                                                                                            4.Copy the API Key and Secret Key and paste into FinTax                                                                                                       5.Ensure the API Restrictions are set to Can Read and IP access restrictions are set to Unrestricted                                                                    &#x20;

**NOTE:** Automatically pulling your withdrawals and deposits is not yet supported. Instead, please add withdrawals and deposits manually or via CSV upload.

### Coinbase

1.Visit [Coinbase Exchange API](https://exchange.coinbase.com/profile/api) page                                                                                                                              2.Click + New API Key                                                                                                                                                        3.Under Permissions select View                                                                                                                                          4.Copy the Passphrase and paste into FinTax                                                                                                               5.Leave the IP whitelist blank                                                                                                                                                      6.Click Create API Key                                                                                                                                                                 7.If applicable, enter your two-factor authentication code                                                                                                     8.Click Add API Key                                                                                                                                                                9.Copy the API Secret and paste into FinTax                                                                                                             10.Click Done11.Copy the API Secret and paste into FinTax

### KuCion

1.Open the [Kucoin API Management](https://www.kucoin.com/account/api) page from your user profile                                                               2.Configure a trading password and 2FA, if necessary                                                                                          3.On the API management page, click the Create API button                                                                                 4.On Kucoin, enter an API name and API passphrase of your choice                                                                      5.On FinTax, enter the API passphrase                                                                                                                                 6.For additional security, ensure the the Trade and Withdraw permissions are disabled for this API key                                                     7.Select No for IP restrictions, and then click Next                                                                                                  8.Enter your Trading Password, Email Verification Code and 2FA code                                                                                                                       9.Click Activate API in the email you receive                                                                                                             10.Copy the Key and Secret into FinTax

Due to a limitation in Kucoins API, transactions over 6 months old will not be synchronized automatically. After adding your Kucoin account you will be redirected to manually add older transactions or reimport your Kucoin account by CSV.

### Bitflyer

1.Login to Bitflyer                                                                                                                                                         2.Navigate to API                                                                                                                                                             3.Click on 'Generate New Key' button                                                                                                                           4.Copy the 'API Key' and 'API Secret' and enter them both here into Crypto Tax Calculator



## Steps to add your exchange transactions

### Binance

1.Visit Transaction History on [Binance](https://binance.com/en/my/wallet/history/deposit-crypto)                                                                                                                      2.Export Transaction Recordsby clicking the top right corner export button (small square icon with an arrow)                                                                                                                                                                                 3.Under "Account" Select All                                                                                                                                        4.Under "Time Range" Select your desired date range                                                                                         5.Under "Coin" Select All                                                                                                                                                        6.Click Generate and wait until it's ready to download.                                                                                          7.Once the Download button appears download the zip file and unzip the file to get the CSV.                      8.Upload the CSV here

### OKX

1.Go to [Trading History](https://www.okx.com/balance/report-center/unified/account-history) in OKX                                                                                                                            2.Download your zip file with your desired time range and unzip it.                                                                 3.Upload he CSV file here

### Bybit

1.To add your Bybit transactions to FinTax, you will need to reformat them into the FinTax CSV format.                          2.Download the XLSX export from the "Assets History" tab of your transactions on [Bybit](https://www.bybit.com/app/wallet/money-record)                               3.Re-format your Bybit transactions into this CSV formatImport the CSV here                                                4.Please see this support guide for any additional details on importing your Bybit transactions to FinTax

### Kraken

1.Export transactions file from your exchange or wallet                                                                                          2.Re-format it using our FinTax CSV template and guide
