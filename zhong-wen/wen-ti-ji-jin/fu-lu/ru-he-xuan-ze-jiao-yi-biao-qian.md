# 如何选择交易标签

欢迎使用FinTax软件。本手册将帮助您理解和使用交易标签，以便更好地管理和分类您的加密货币交易，确保准确的税务处理。

### 1 交易方向和交易类型标签

本部分帮助您手动添加交易。

在手动添加交易时，您首先需要在Transaction tags中选择两类Tag：交易方向和交易类型。交易方向只有buy和sell，指这笔交易使得您账户余额增加或减少；交易类型则指这笔交易属于何种交易（现货交易、期货交易、永续合约交易等）。

如果您从交易所自动导入交易，您不需要编辑交易方向和交易类型，系统会自动识别。

_**1.1 交易的方向**_

* **buy (购买)**

定义：您的账户中加密货币增加了。

示例：用美元买入比特币，账户中比特币数量增加，这笔交易方向应标记为buy。

* **sell (出售)**

定义：您的账户中加密货币减少了。

示例：将比特币卖出换成美元，账户中比特币数量减少，这笔交易方向应标记为sell。



_**1.2 交易的类型**_

* **transfer in (转入)**

定义：将加密货币从外部钱包或平台转入当前钱包或账户。

示例：从硬件钱包转账比特币到交易所账户，应标记为transfer in。

* **transfer out (转出)**

定义：将加密货币从当前钱包或账户转出到外部钱包或平台。

示例：将比特币从交易所账户转到个人钱包，应标记为transfer out。

* **send (发送)**

定义：将加密货币发送给其他用户或地址。

示例：将以太坊发送给朋友，应标记为send。

* **receive (接收)**

定义：从其他用户或地址接收加密货币。

示例：接收朋友发送的比特币，应标记为receive。

* **delivery short (平仓合约或永续合约)**

定义：平仓合约，结清已开立的合约头寸的行为，包括平仓普通合约和平仓永续合约。

示例：如果您之前购买了10个比特币的期货合约（多头头寸），现在卖出同等数量的期货合约以结清头寸，则卖出的这一笔交易标记为delivery short。相反，如果您之前卖出了10个比特币的期货合约（空头头寸），现在买入同等数量的期货合约以结清头寸，买入的这一笔交易也标记为delivery short。

* **interest deduction (利息扣除)**

定义：支付或收取的利息费用。

示例：支付在杠杆交易中的利息，应标记为interest deduction。

* **spot (现货交易)**

定义：使用法币或使用一种加密货币以市场价格买卖另一种加密货币。

示例：在交易所中以当前市场价格用法币购买以太坊，应标记为spot；在交易所中以当前市场价格用USDT兑换比特币，也应标记为spot。

* **fee (费用)**

定义：在交易过程中支付的手续费。

示例：在比特币交易的过程中支付给交易所的手续费，应标记为fee。

* **funding fee income (永续合约资金费率收入)**

定义：从永续合约中取得的资金费用收入。

示例：您买入一张看空比特币的永续合约，并通过这张合约收取资金费用，收取的费用应标记为funding fee income。

* **funding fee expense (永续合约资金费率支出)**

定义：从永续合约中取得的资金费用支出。

示例：您买入一张看多比特币的永续合约，并因这张合约支出资金费用，支出的费用应标记为funding fee expense。

* **swap (永续合约交易)**

定义：使用加密货币买卖永续合约。

示例：使用100USDT买入1张比特币永续合约，这笔交易应标记为swap。

* **future (期货合约交易)**

定义：使用加密货币买卖期货（非永续）合约。

示例：购买一张到期时以某价格交割的比特币期货合约，应标记为future。

* **margin (保证金交易)**

定义：使用借入资金进行加密货币交易。

示例：您利用合约借入比特币并进行杠杆交易，开杠杆的交易动作应标记为margin。

* **transfer (转账)**

定义：钱包或账户之间的转账操作。

示例：将以太坊从一个钱包转移到另一个钱包，应标记为transfer。

* **deposit (存款)：**

定义：将资金存入您的加密货币账户。

示例：将法币存入交易所账户以购买加密货币，应标记为deposit。

* **withdrawal (取款)：**

定义：从您的加密货币账户中提取资金。

示例：从交易所账户中提取法币至银行账户，应标记为withdrawal。



### 2 税务和业务标签

_**2.1 税务类型标签**_

FinTax在申报时会根据不同交易类型，自动将交易归属为不同的税务事件。您需要在此处再次核对您的交易与系统识别到的税务事件的描述是否相符。尤其是当您经营商业业务或以加密货币形式接收工资收入时，您需要找到与商业业务相关的交易，以及以加密货币形式入账的工资，将它们手动标记，以便正常汇算税款。

* **Buy/sell (with fiat) and trade crypto for crypto (将加密货币兑换成法币，将法币兑换成加密货币，以及将一种加密货币兑换成另一种加密货币)：**

定义：使用法币购买或卖出加密货币，或使用一种加密货币交易另一种加密货币。

示例：用美元购买比特币或用比特币交易以太坊。

* **Rewards from hard forks and ICO (硬分叉和ICO奖励)：**

定义：通过加密货币硬分叉或首次代币发行（ICO）获得的奖励。

示例：在比特币现金硬分叉时获得的比特币现金，或在ICO期间购买代币并获得的额外奖励。

* **Receiving crypto gifts, wallet transfers (between your own wallet), and personal use (接收加密货币礼物、在自己的钱包之间转账和个人使用)：**

定义：接收他人赠送的加密货币；在自己的不同钱包之间进行转账；未出于投资或营利目的，将加密货币单纯用于个人消费。

示例：

接受朋友赠送的比特币。

将比特币从硬件钱包转移到软件钱包。

为享受咖啡店的优惠活动，先用法币购买比特币，后马上用比特币购买咖啡。

* **For payment (用于支付)：**

定义：使用加密货币进行支付。

示例：用以太坊支付服务费用或商品费用。

* **Donate or give crypto as a gift (捐赠或赠送加密货币作为礼物)：**

定义：将加密货币捐赠给组织或个人，或作为礼物赠送。

示例：将比特币捐赠给慈善机构或送给朋友作为生日礼物。

* **Airdrops, mining, lending and staking rewards (空投、挖矿、借贷和质押奖励)：**

定义：通过空投、挖矿、借贷或质押获得的加密货币奖励。

示例：接收项目方的空投代币，通过挖矿获得的比特币，通过借贷平台获得的利息或通过质押获得的奖励。

* **Margin, futures, and derivatives trading (保证金、期货和衍生品交易)：**

定义：涉及使用保证金、期货合约或其他衍生品的交易活动。

示例：使用保证金进行的比特币交易、购买以太坊期货合约或进行加密货币期权交易。

* **Salary and employment-related payments (工资和与就业相关的支付)：**

定义：通过工资或其他与就业相关的活动获得的加密货币支付。

示例：以加密货币支付的工资或通过自由职业获得的加密货币报酬。

* **Income/expense from other activities (其他活动收入/支出)**：

定义：任何通过其他上述没有包括的活动获得的加密货币收入/支出。

示例：如在经营个人业务中以加密货币为支付媒介购买/出售商品和服务等。



_**2.2 业务类型标签-工资**_

如果您以加密货币形式收到工资和与就业相关的支付，您需要选择以下标签。

首先，您需要判断支付工资的Employer is domestic or abroad，如果是国内雇主，您还需要进一步选择这笔收入的来源，以完成税务报告。收入来源分为以下5种：

* **Sacrifice agreement (牺牲协议)**

定义：员工同意将部分工资牺牲，并以加密货币形式支付。

示例：员工同意减少部分工资以换取更多的公司股票或加密货币。

* **Salary or wages (工资或薪金)**

定义：员工通过工作获得的工资或薪金，本身就以加密货币支付。

示例：员工每月收到公司支付的比特币工资。

* **Allowances, earnings, tips, director's fees etc (津贴、收入、小费、董事费等)：**

定义：包括津贴、其他收入、小费和董事费在内的各种支付，以加密货币支付。

示例：员工收到的以太坊形式的交通补贴或董事会成员收到的比特币形式的董事费。

* **Employer lump sum payments (雇主一次性付款)：**

定义：the lump sum payments which you received from your employer for unused annual leave or unused long service leave，以加密货币支付。

* **Employment termination payments (etp) (雇佣终止付款)：**

定义：员工离职时收到的终止付款，以加密货币支付。



_**2.3 业务类型标签-经营业务**_

如果您是业余投资者，您的加密货币交易一般标记为non business；如果您专业经营加密货币业务，如短线交易、质押、参加空投活动获利等，您可能需要标注您的交易类型为business。如果您不知道自己是否专门经营业务，您可以咨询FinTax税务咨询团队，或咨询您的税务师。

如果您的交易类型为business，您需要选择收入和费用的类型，以完成税务申报。

收入：选择Other business income

费用：您根据具体支出的费用类型，选择不同的费用标签，以从你的商业活动收入中抵扣部分应纳税款。注意：并非每一笔支付的费用都可以抵扣，如果不是在商业活动中发生的费用或不满足抵扣条件，您可将这笔支出在上一步选择为non business。

* **Opening Stock (期初存货)**

定义：本纳税年度初存货的价值。

* **Purchases and Other Costs (采购和其他费用)**

定义：指用于制造、销售或交换以获取业务毛收入或收益的直接材料成本，包括内部运输和在年度内开始或收购业务时获得的存货成本。也可能包括一些劳动力和服务费用，如果这些费用记录在销售成本账户中，不包括在承包商、分包商和佣金费用中。

* &#x20;**Closing Stock (上一年度期末存货)**

定义：上一纳税年度末存货的价值。

* **Cost of Sales (销售成本)**

公式：【销售成本】=【期初存货】+【采购和其他费用】-【期末存货】

* **Foreign Resident Withholding Expenses (excluding capital gains) (外国居民预提费用，不含资本利得)**

定义：外国居民预提费用。

* **Contractor, Sub-contractor and Commission Expenses (承包商、分包商和佣金费用)**

定义：根据合同提供的劳力和服务的费用，例子包括支付给自雇人士的费用，如顾问费、承包费用，包括PAYG自愿协议下的支付，及劳务安排下的支付，佣金支付给未领取预付金的人，代理费用（如广告代理提供的服务），服务费（如设备服务费），管理费和顾问费。

* &#x20;**Superannuation Expenses (养老费)**

定义：雇主为员工支出的退休金等可扣除费用。

* **Bad Debts (坏账)**

定义：正常业务借出的款项，若存在业务损失的情况，可扣除。

* &#x20;**Lease Expenses (excluding real estate) (租赁费用，不含房地产)**

定义：融资租赁和经营租赁资产的支出，如汽车和工厂。不包括房地产租赁成本。

* **Rent Expenses (including real estate) (租金费用，包括房地产)**

定义：用于生产收入的土地和建筑物租金支出，包括房地产租赁成本。

* **Interest Expenses within Australia (澳大利亚境内的利息费用)**

定义：包括在澳大利亚境内借款以获得用于业务的收入产生资产、融资业务运营或满足当前业务费用的利息。

* **Interest Expenses Overseas (海外利息费用)**

定义：包括从海外借入资金所产生的任何利息，这些资金用于购买您企业中使用的创收资产、为企业运营提供资金或支付当前的企业开支。

* **Depreciation Expenses (折旧费)**

定义：资产在使用过程中由于磨损、消耗或自然损坏而逐渐减值的费用（一般不以加密货币形式呈现）

* **Motor Vehicle Expenses (机动车辆费用)**

定义：与机动车辆相关的费用，包括油费、维修费、保险费等。

* **Repairs and Maintenance (维修和保养)**

定义：与收入相关的维修保养费用，不包括资本性质或私人使用的项目费用。

* **Home Office Expenses (家庭办公费用)**

定义：如果房屋的一部分被专门用作营业场所并且用于业务活动，则以下开支可扣除：入住费用（包括租金、按揭利息、差饷及房屋及物品保险）、日常开支（包括电费、清洁费、折旧费、租赁费以及办公室家具和陈设的维修费用）。

* **All Other Expenses (所有其他费用)**

定义：未包含在上述范围内的所有其他费用，如办公用品、外汇损失等。

&#x20;

通过这些标签，您可以更有效地管理和记录您的加密货币交易和业务活动。无论是个人投资者还是企业用户，都可以使用这些标签清晰地分类和追踪各类交易，便于财务分析和报税。FinTax会根据这些标签自动识别和分类不同的交易类型，帮助您生成准确的税务报告。

如果有任何问题或需要进一步的帮助，请随时联系我们的客户支持团队。感谢您选择FinTax！
