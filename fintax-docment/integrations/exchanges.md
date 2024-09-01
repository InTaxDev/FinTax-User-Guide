# Exchanges

## Which exchanges does FinTax support?

FinTax currently supports the following:

**Binance,** **Okx**, _BIT_, **Bybit,** **Kraken**, **CoinSpot**, **Swyftx**, **Huobi**, **Gate.io**,&#x20;

**Bitfinex**, **Bitget**, Upbit, **CoinEx**,**Crypto.com**, OSL, **Coinbase**. **KuCoin**,&#x20;

**Bitflyer**, **AscendEX**, _**Bithumb**_, **Bitstamp**, **CoinList**, **Copper**, _**dYdX**_,

Fireblocks, Galaxy, **Gemini**, Indadax, _**ItBit**_,  LMAX(DIGITAL), _MEXC_

LTP, _**Okcoin**_, **Poloniex**, _**sFOX**_

## How to add your Exchange account?

### Binance

1.Open the Binance [Account API ](https://accounts.binance.com/en/login?return\_to=aHR0cHM6Ly93d3cuYmluYW5jZS5jb20vZW4vbXkvc2V0dGluZ3MvYXBpLW1hbmFnZW1lbnQ=)page

2.Select Create Tax Report API (this is limited to read-only access)

3.If applicable, enter your two-factor authentication code and email verification code

4.Copy the API Key and Secret and paste into Fintax

### Okx&#x20;

1.Go to [Trading History ](https://www.okx.com/balance/report-center/unified/account-history)in OKX

2.Download your zip file with your desired time range and unzip it.

3.Upload the CSV file here

### BIT

The selected exchange is a Beta version.

&#x20;1.UIDs are used to identify accounts and troubleshoot issues, and can be found on the Security Settings page

### Bybit

1.Download the **XLSX export** from the **"Assets History"** tab of your transactions on [Bybit](https://www.bybit.com/app/wallet/money-record)

2.Re-format your Bybit transactions into [this CSV format](https://support.cointracker.io/hc/en-us/articles/4413071299729-Converting-transaction-history-CSVs-to-the-CoinTracker-CSV-format)

3.Import the CSV here

### Kraken

1.Log in to Kraken [Kraken](https://www.kraken.com/)

2.Click on your name in the upper-right corner of the page and choose Security and then choose API

3.Select Add key

4.Enable the following permissions:\
Query funds\
Query closed orders & trades\
Query ledger entries

5.Select Generate key

6.Copy the API Key and Private Key and paste into Fintax

### CoinSpot

1.Open the CoinSpot [API page](https://www.coinspot.com.au/my/api)&#x20;

2.Click the Generate New Api Key button&#x20;

3.Enter any name, and select the Read Only API key type&#x20;

4.If applicable, enter your Two Factor Code&#x20;

5.Confirm the new API key by email&#x20;

6.Reveal the API secret, and copy the Key and Secret

### Swyftx

1.Open [Swyftx Manage Keys](https://trade.swyftx.com.au/profile/api/) page&#x20;

2.Click "Generate NEW KEY" button&#x20;

3.Enter a label (example: Fintax) and click "NEXT" button

&#x20;4.Select check boxes on: Account.Tax Report, Account.Balance, Account.Read, Address.Read, Orders.Read, Funds.Read and click "NEXT" button&#x20;

5.Enter Swyftx account password and click "NEXT" button&#x20;

6.Copy API KEY7.On this page paste it in the field and click "Add Account" button

### Huobi

1.Follow the instructions on [how to create a Huobi API key](https://www.htx.com/support/en-us/detail/360000203002)\
2.Copy and paste the API key and secret to Fintax here

### Gate.io

1.Follow the instructions on [how to create API V4 Key](https://support.cointracker.io/hc/en-us/articles/4413049686417-Integrating-Gate-io-with-APIv4-keys)\
2.Copy the Key and Secret

### Bitfinex

1.Open the [Bitfinex API](https://www.bitfinex.com/api) page.&#x20;

2.Select Create New Key&#x20;

3.Keep the default permissions unchanged - all 'Read' permissions enabled.&#x20;

4.Enter a label for the API key, such as 'FinTax'&#x20;

5.Select Generate API key&#x20;

6.If applicable, enter your two-factor authentication code.&#x20;

7.Confirm the new API key from the verification email you receive from Bitfinex&#x20;

8.Copy the API Key and API Key Secret.

### Bitget

1.Login to Bitget

2.Navigate to API management from the navigation bar at the top

3.From the drop-down menu, choose API Management

4.Click on Create a New API

5.Click on System-Generated API Key

6.In the pop-up window, create a passphrase for your API

7.Under Permissions, select Read-only across all checkboxes

8.Complete the two-factor verification and click 'Next'.

9.Copy across your API key and Secret

### CoinEX

1.Download the CSV export of your transactions from [CoinEx](https://www.coinex.com/)

2.Re-format it into the CoinTracker CSV format [like this](https://support.cointracker.io/hc/en-us/articles/4413071299729-Converting-transaction-history-CSVs-to-the-CoinTracker-CSV-format)

3.Import this file here

### Crypto.com

**NOTE:** These instructions apply to the Crypto.com exchange, please see instructions for the Crypto.com app available to US users here.

1.Within the Crypto.com Exchange web app, click your Profile (upper right corner) 2.Select Settings, and then select API Keys 3.Select Create a new API key, enter a label such as "FinTax," and enter your 2FA code 4.Copy the API Key and Secret Key and paste into FinTax 5.Ensure the API Restrictions are set to Can Read and IP access restrictions are set to Unrestricted

**NOTE:** Automatically pulling your withdrawals and deposits is not yet supported. Instead, please add withdrawals and deposits manually or via CSV upload.

### Coinbase

1.Visit [Coinbase Exchange API](https://exchange.coinbase.com/profile/api) page&#x20;

2.Click + New API Key

&#x20;3.Under Permissions select View

&#x20;4.Copy the Passphrase and paste into FinTax&#x20;

5.Leave the IP whitelist blank

&#x20;6.Click Create API Key&#x20;

7.If applicable, enter your two-factor authentication code&#x20;

8.Click Add API Key

&#x20;9.Copy the API Secret and paste into FinTax&#x20;

10.Click Done11.Copy the API Secret and paste into FinTax

### KuCion

1.Open the [Kucoin API Management](https://www.kucoin.com/account/api) page from your user profile 2.Configure a trading password and 2FA, if necessary 3.On the API management page, click the Create API button 4.On Kucoin, enter an API name and API passphrase of your choice 5.On FinTax, enter the API passphrase 6.For additional security, ensure the the Trade and Withdraw permissions are disabled for this API key 7.Select No for IP restrictions, and then click Next 8.Enter your Trading Password, Email Verification Code and 2FA code 9.Click Activate API in the email you receive 10.Copy the Key and Secret into FinTax

Due to a limitation in Kucoins API, transactions over 6 months old will not be synchronized automatically. After adding your Kucoin account you will be redirected to manually add older transactions or reimport your Kucoin account by CSV.

### Bitflyer

1.Login to Bitflyer&#x20;

2.Navigate to API&#x20;

3.Click on 'Generate New Key' button&#x20;

4.Copy the 'API Key' and 'API Secret' and enter them both here into Crypto Tax Calculator

### AscendEX

1.Log in to your AscendEX account

2.Click on the avatar icon in the top right corner

3.Click on 'API Setting' and click 'New API key'

4.Check the ‘View’ Permission for the key, and enter your email verification code and 2FA code

5.Click 'Generate API key'

6.Copy across your API key and Secret

### Bitstamp

1.Open the [Bitstamp API Access](https://www.bitstamp.net/account/security/api/) page.

2.If you already have existing API keys, select **New API Key**

3.Enable the following permissions:

* Account balance
* User transactions

4.If applicable, enter your Two-Factor Authentication Code

5.Select **Generate Key**

6.Select **Activate**

7.Confirm the new API key from the verification email you receive from Bitstamp

8.Copy the API Key and API Key Secret

### CoinList

1.Log in to your CoinList account

2.Click on the dropdown menu in the upper right of the CoinList Pro platform

3.Select 'API' and then click 'Create New Key'

4.Generate a unique API key with 'read only' permissions

### Copper

1.In Crypto Tax Calculator select the corresponding network (the left of these instructions)

2.Find the xpub, ypub or zpub wallet public key for the network that the assets are held on (e.g. BTC xpub key)

3.Once found, copy this public key, paste it into the form on this page, and click 'Import Wallet' to sync your transactions

### dYdX

### Fireblocks



### Gemini

1.Open the [Gemini API Settings](https://exchange.gemini.com/settings/api) page.

2.Select **Primary** as scope.

3.Select **Create a New API Key**.

4.If applicable, enter your two-factor authentication code

5.Copy the API Key and API Secret

6.Under API Key Settings, disable Trading and enable Auditor

7.Select the checkbox indicating that you've copied the API secret and select Confirm.

### MEXC

1.Log into your MEXC account

2.In the top right of the screen, hover over the account picture and select 'API' from the dropdown list

3.In the 'API Management / Create API Key' screen, under the 'Spot' heading, select 'Account: Read account information' and 'Trade: Read order information'

4.In the Notes, provide a nickname for the API key, such as 'Crypto Tax Calculator' and click the button 'Create'

5.Verify your account information in MEXC

6.Copy the 'Access Key' and 'Secret Key' and enter them both into Crypto Tax Calculator

### Poloniex

1.Open the [Poloniex API Keys](https://poloniex.com/apiKeys) page.

2.Select **Create New Key** button

3.If applicable, enter your two-factor authentication code.

4.Confirm the new API key from the verification email you receive from Poloniex

5.On the [API Keys](https://poloniex.com/apiKeys) page, deselect the new API key

6.Copy the API Key and Secret



## Steps to add your exchange transactions

### Binance

1.Visit Transaction History on [Binance](https://binance.com/en/my/wallet/history/deposit-crypto)&#x20;

2.Export Transaction Recordsby clicking the top right corner export button (small square icon with an arrow)&#x20;

3.Under "Account" Select All&#x20;

4.Under "Time Range" Select your desired date range

&#x20;5.Under "Coin" Select All&#x20;

6.Click Generate and wait until it's ready to download.&#x20;

7.Once the Download button appears download the zip file and unzip the file to get the CSV. 8.Upload the CSV here

### OKX

1.Go to [Trading History](https://www.okx.com/balance/report-center/unified/account-history) in OKX&#x20;

2.Download your zip file with your desired time range and unzip it.

3.Upload he CSV file here

### Bybit

1.To add your Bybit transactions to FinTax, you will need to reformat them into the FinTax CSV format.&#x20;

2.Download the XLSX export from the "Assets History" tab of your transactions on [Bybit](https://www.bybit.com/app/wallet/money-record)&#x20;

3.Re-format your Bybit transactions into this CSV formatImport the CSV here&#x20;

4.Please see this support guide for any additional details on importing your Bybit transactions to FinTax

### Kraken

1.Log in to your Kraken account and click on the 'History' tab in the navbar menu, then click on the 'Export' tab

2.Select 'Ledgers' (not the same as Trades) then select the time period that you traded, check the 'Select All' Check Box, and click the 'Submit' button.

3.Wait a few seconds and click on Download (maybe you will have to refresh the page, to see the Download link). This will download the CSV in a .zip file.

4.Unzip the file.

5.Upload the CSV(s) here to FinTax.

### CoinSpot

1.Open the CoinSpot [**Order History**](https://www.coinspot.com.au/my/orders/history) page

2.Click Download CSV

3.Import the downloaded file below

### Swyftx

1.Export transactions file from your exchange or wallet

2.Re-format it using our FinTax CSV template and guide

### Huobi

1.Export transactions file from your exchange or wallet

2.Re-format it using our FinTax CSV template and guide

### Gate.io

1.Log in to your [Gate.io](http://gate.io/) account and head to [https://www.gate.io/myaccount/mypurselog](https://www.gate.io/myaccount/mypurselog) . You can also access this page from the sidebar menu > Transaction History.

2.Select ‘All’ for Coin and ‘All’ for Filter.

3.Click ‘Filter’ > Download

4.You can also click ‘Request batch data’ in the top right corner.

5.Select ‘All’ for Coin and submit the application.

6.You can download 90 days of transaction history each time. If you have more, repeat the steps for different periods.

### Bitfinex

1.Login to Bitfinex,In the top right corner, hover over 'Wallet' and select 'Reports' from the dropdown. This should navigate you to '[https://report.bitfinex.com](https://report.bitfinex.com/)'.

2.Click on the calendar icon at the top of the page.

3.Select a custom range of dates that include your entire trading history.

4.Click on the 'Export' button, a popup should appear.

5.In the 'Data to Export' field select 'Ledgers' and 'Movements' only. Select the 'Date Format' to be 'DD-MM-YY'. Check the box which says 'Display Milliseconds'

6.Click the 'Export' button at the bottom of the popup. This will generate CSV files which will be sent to your EMAIL.

7.In your email client, open the email and click 'Download CSV'. This will download a .zip file containing two CSVs (one for ledgers and one for movements).

### Bitget

1.Export transactions file from your exchange or wallet

2.Re-format it using our FinTax CSV template and guide

### CoinEx

1.Download the CSV export of your transactions from [CoinEx](https://www.coinex.com/)

2.Re-format it into the FinTax CSV format

3.Import this file here

### Crypto.com

**Note:** Make sure to select the "Transaction" report type when exporting, as we **do not** accept other types of reports such as trade reports, deposit and withdrawal reports, and order reports.

1.[On the Crypto.com exchange web app](https://crypto.com/exchange/wallet/transactions), click on **Wallet** on the left hand side and choose the **Transactions** tab for your reports

2.Choose your desired time range in **From** and **To**

3.Set **Transaction Type** to All

4.Set **Instrument to All**

5.Click **Export** and receive the zip file

6.Unzip the file and upload the Tranasction CSV file only

### Coinbase

1.Visit [Coinbase Statements page](https://accounts.coinbase.com/statements)

2.Navigate to Generate custom statement

3.Set Asset: **All assets**

4.Set Transaction type: **All Transactions**

5.Set Date: **Your Desired Year**

6.Set Format: **CSV**

7.Click Generate and upload CSV here

### Bitflyer

1.Visit the bitFlyer USA [trade report page](https://bitflyer.com/en-us/ex/tradehistory)

2.Click **Export All Transactions**

3.Import it here

### AscendEX&#x20;

1.Log in to your AscendEX account

2.Select 'My Order' ([https://bitmax.io/en/order/cash-order](https://bitmax.io/en/order/cash-order))

3.Click 'Request to Export'

4.You can then click the button on the right 'My Exported Files' and download the file once complete

5.Upload the downloaded CSV file directly here into Crypto Tax Calculator

### Bithumb

1.Export transactions file from your exchange or wallet

2.Re-format it using our FinTax CSV template and guide

### Bitstamp

1.Log in to your Bitstamp account

2.Go to the Transactions page by clicking the user icon in the top-right corner, then 'Activity', and then 'Transaction history' in the left sidebar ([https://www.bitstamp.net/account/transactions](https://www.bitstamp.net/account/transactions))

3.Click the 'Open export options' button

4.Select the 'Date range' that covers all your transaction history

5.Choose 'All' for the currencies

6.Choose 'All' for the Transaction types

7.Choose 'RFC 4180 (new)' for the CSV format

8.Click the 'Export selection' button to download the CSV file

9.Upload this CSV here into FinTax

### CoinList

1.Log in to your CoinList account

2.Click on the dropdown menu in the upper right of the CoinList platform and navigate to 'Wallets'

3.Select your wallets and set the time range of the transaction data and click 'Download CSV'

4.Upload CSV file into FinTax

### dYdX

1.Visit [trade.dYdX.exchange](http://trade.dydx.exchange/) and connect your wallet(s)

2.Click on ‘Portfolio’ in the menu bar

3.Select ‘History’ in the side panel

4.Click on ‘Export’ on the top right corner of the screen

5.Download all 3 CSV’s available: Transfers, Trades, Funding

6.Upload the extracted files to Crypto Tax Calculator

**Note:** Currently, you will have a missing purchase history issue due to the way dYdX records the short trades. We are working on a resolution. For now, you can potentially calculate the PnL and use our manual CSV to add a Realized Loss/Profit for the short trade.

### Fireblocks

1.Download the CSV export of your transactions from [itBit](https://www.itbit.com/)

2.Re-format it into the FinTax CSV format

### Gemini

1.Visit [**Statements and History**](https://exchange.gemini.com/settings/documents)

2.Click the “Transaction History” tab.

3.Click the download button next to “Exchange Transaction History” and select your desired date range and download as .xlsx file.

### ItBit

1.Download the CSV export of your transactions from [itBit](https://www.itbit.com/)

2.Re-format it into the FinTax CSV format

3.Import this file here

### MEXC

1.Log in to your MEXC account. There are four different files we require based on your trading history.

2.For futures trading data: On the top menu bar click 'Orders' and select 'Futures Orders'.

3.Select 'Order & Trade History' and click the 'Export Order History' button.

4.In the popup window, select the time range you wish to download, select ‘EXCEL’ for the Export Format and press the 'Export' button to export your transaction records.

5.For spot trading data: On the top menu bar click 'Orders' and select 'Spot Orders'.

6.Select 'Trade History' and click the 'Export' button.

7.In the popup window, select the time range you wish to download, and press the 'Generate’ button to export your transaction records.

8.For deposit history data: On the top menu bar click 'Wallets' and select 'Funding History'.

9.Select 'Deposit' and click the 'Export' button.

10.In the popup window, select the time range you wish to download, deselect ‘Encrypt the file’ and press the 'Generate’ button to export your deposit records.

11.For withdrawal history data: On the top menu bar click 'Wallets' and select 'Funding History'.

12.Select 'Withdrawal' and click the 'Export' button.

13.In the popup window, select the time range you wish to download, deselect ‘Encrypt the file’ and press the 'Generate’ button to export your withdrawal records.

### Okcoin

1.Export transactions file from your exchange or wallet

2.Re-format it using our FinTax CSV template and guide

### Poloniex

1.Request a complete transaction history from Poloniex ([US users](https://support.poloniexus.circle.com/hc/en-us/requests/new), [non-US users](https://support.poloniex.com/hc/en-us/requests/new))

2.Upload the CSV to the importer here

### sFOX

1.Export transactions file from your exchange or wallet

2.Re-format it using our FinTax CSV template and guide
