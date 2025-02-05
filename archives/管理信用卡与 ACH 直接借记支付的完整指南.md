# 管理信用卡与 ACH 直接借记支付的完整指南

本文将为您详细介绍如何在 AWS Billing and Cost Management 控制台中管理信用卡和 ACH 直接借记支付方式，帮助您轻松完成支付设置与更新。

---

## 如何添加信用卡

通过 AWS Billing and Cost Management 控制台，您可以快速向您的账户添加信用卡。以下是具体步骤：

1. 登录 **AWS Management Console**，并访问 [AWS Billing and Cost Management 控制台](https://console.aws.amazon.com/costmanagement/)。
2. 在左侧导航栏中，选择 **Payment preferences**（付款首选项）。
3. 点击 **Add payment method**（添加付款方式）。
4. 输入您的信用卡信息。
5. （可选）勾选 **设为默认付款方式**，将此信用卡设置为默认支付方式。
6. 输入信用卡的账单地址。
7. （可选）添加标签键和值（最多 50 个标签）。
8. 验证信息后，点击 **添加付款方式**。

---

## 如何更新信用卡信息

您可以随时更新信用卡的过期时间、姓名、地址和电话号码：

1. 访问 [AWS Billing and Cost Management 控制台](https://console.aws.amazon.com/costmanagement/)。
2. 在导航栏中选择 **Payment preferences**（付款首选项）。
3. 在 **付款方式** 部分，选择需要编辑的信用卡，点击 **编辑**。
4. 更新所需信息并保存更改。

**注意**：当您更新信用卡时，AWS 将从上个月未付发票中扣除相应金额。

---

## 如何排查信用卡未验证问题

若您的信用卡未通过验证，请按照以下步骤操作：

1. 访问 [AWS Billing and Cost Management 控制台](https://console.aws.amazon.com/costmanagement/)。
2. 选择 **Payment preferences**（付款首选项）。
3. 在 **付款方式** 部分，点击 **验证** 并按照提示操作。
4. 如果验证失败：
   - 删除该付款方式。
   - 重新添加信用卡并完成验证。

**注意**：部分银行可能要求额外验证步骤，请参考银行相关说明。

---

## 如何删除信用卡

在删除信用卡前，请确保已设置其他有效的默认支付方式：

1. 访问 [AWS Billing and Cost Management 控制台](https://console.aws.amazon.com/costmanagement/)。
2. 选择 **Payment preferences**（付款首选项）。
3. 在 **付款方式** 部分，选择要删除的信用卡并点击 **删除**。
4. 在弹出的确认框中，点击 **删除**。

---

## 管理 ACH 直接借记支付方式

如果您的账户符合以下条件，您可以通过 ACH 直接借记使用美国银行账户支付：

- 账户创建时间超过 60 天。
- 过去 12 个月内至少全额支付一次发票。
- 过去 12 个月内累计支付金额超过 100 美元。
- 美元为您的首选币种。

### 添加 ACH 直接借记账户

1. 访问 [AWS Billing and Cost Management 控制台](https://console.aws.amazon.com/costmanagement/)。
2. 选择 **Payment preferences**（付款首选项）。
3. 点击 **Add payment method**（添加付款方式）。
4. 选择 **Bank account (ACH)**（银行账户 [ACH]）。
5. 输入银行账户信息，包括路由号码和账户号码。
6. （可选）设置为默认付款方式。
7. 输入账单地址并同意条款后，点击 **添加付款账户**。

### 更新 ACH 直接借记账户

1. 访问 [AWS Billing and Cost Management 控制台](https://console.aws.amazon.com/costmanagement/)。
2. 选择 **Payment preferences**（付款首选项）。
3. 在 **付款方式** 部分，选择直接借记账户并点击 **编辑**。
4. 更新信息后保存更改。

---

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

---

通过以上步骤，您可以在 AWS 平台上高效管理信用卡和 ACH 直接借记支付方式。如果您遇到任何问题，请参考 AWS 官方文档或联系客服支持。