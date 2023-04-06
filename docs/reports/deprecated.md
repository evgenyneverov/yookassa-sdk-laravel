# [YooKassa API SDK](../home.md)

# Deprecated Elements
### Table of Contents
* [lib/Model/ConfirmationType.php](../../lib/Model/ConfirmationType.php)
* [lib/Model/Payment.php](../../lib/Model/Payment.php)
* [lib/Model/PaymentData/PaymentDataWechat.php](../../lib/Model/PaymentData/PaymentDataWechat.php)
* [lib/Model/PaymentMethod/PaymentMethodBankCard.php](../../lib/Model/PaymentMethod/PaymentMethodBankCard.php)
* [lib/Model/PaymentMethod/PaymentMethodFactory.php](../../lib/Model/PaymentMethod/PaymentMethodFactory.php)
* [lib/Model/PaymentMethod/PaymentMethodWechat.php](../../lib/Model/PaymentMethod/PaymentMethodWechat.php)
* [lib/Model/PaymentMethodType.php](../../lib/Model/PaymentMethodType.php)
* [lib/Model/Payout/PayoutCancellationDetailsPartyCode.php](../../lib/Model/Payout/PayoutCancellationDetailsPartyCode.php)
* [lib/Model/Receipt.php](../../lib/Model/Receipt.php)
* [lib/Model/Refund.php](../../lib/Model/Refund.php)
* [lib/Model/Requestor.php](../../lib/Model/Requestor.php)
* [lib/Model/RequestorInterface.php](../../lib/Model/RequestorInterface.php)

<a id="lib/Model/ConfirmationType.php"></a>
#### [lib/Model/ConfirmationType.php](../../lib/Model/ConfirmationType.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 52 | \YooKassa\Model\ConfirmationType::CODE_VERIFICATION | Будет удален в будущих версиях |
<a id="lib/Model/Payment.php"></a>
#### [lib/Model/Payment.php](../../lib/Model/Payment.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 710 | \YooKassa\Model\Payment::setRequestor() | Не используется. Будет удален в следующих версиях |
| 719 | \YooKassa\Model\Payment::getRequestor() | Не используется. Будет удален в следующих версиях |
<a id="lib/Model/PaymentData/PaymentDataWechat.php"></a>
#### [lib/Model/PaymentData/PaymentDataWechat.php](../../lib/Model/PaymentData/PaymentDataWechat.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 34 | \YooKassa\Model\PaymentData\PaymentDataWechat | Класс будет удалён в одной из будущих версий. |
<a id="lib/Model/PaymentMethod/PaymentMethodBankCard.php"></a>
#### [lib/Model/PaymentMethod/PaymentMethodBankCard.php](../../lib/Model/PaymentMethod/PaymentMethodBankCard.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 62 | \YooKassa\Model\PaymentMethod\PaymentMethodBankCard::getLast4() | Будет удален в следующих версиях |
| 73 | \YooKassa\Model\PaymentMethod\PaymentMethodBankCard::getFirst6() | Будет удален в следующих версиях |
| 83 | \YooKassa\Model\PaymentMethod\PaymentMethodBankCard::getExpiryYear() | Будет удален в следующих версиях |
| 93 | \YooKassa\Model\PaymentMethod\PaymentMethodBankCard::getExpiryMonth() | Будет удален в следующих версиях |
| 103 | \YooKassa\Model\PaymentMethod\PaymentMethodBankCard::getCardType() | Будет удален в следующих версиях |
| 113 | \YooKassa\Model\PaymentMethod\PaymentMethodBankCard::getIssuerCountry() | Будет удален в следующих версиях |
| 123 | \YooKassa\Model\PaymentMethod\PaymentMethodBankCard::getIssuerName() | Будет удален в следующих версиях |
| 133 | \YooKassa\Model\PaymentMethod\PaymentMethodBankCard::getSource() | Будет удален в следующих версиях |
| 45 | \YooKassa\Model\PaymentMethod\PaymentMethodBankCard::ISO_3166_CODE_LENGTH | Будет удален в следующих версиях |
<a id="lib/Model/PaymentMethod/PaymentMethodFactory.php"></a>
#### [lib/Model/PaymentMethod/PaymentMethodFactory.php](../../lib/Model/PaymentMethod/PaymentMethodFactory.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 39 | \YooKassa\Model\PaymentMethod\PaymentMethodFactory::YANDEX_MONEY | Для поддержки старых платежей |
<a id="lib/Model/PaymentMethod/PaymentMethodWechat.php"></a>
#### [lib/Model/PaymentMethod/PaymentMethodWechat.php](../../lib/Model/PaymentMethod/PaymentMethodWechat.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 34 | \YooKassa\Model\PaymentMethod\PaymentMethodWechat | Класс будет удалён в одной из будущих версий. |
<a id="lib/Model/PaymentMethodType.php"></a>
#### [lib/Model/PaymentMethodType.php](../../lib/Model/PaymentMethodType.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 86 | \YooKassa\Model\PaymentMethodType::WECHAT | Будет удален в следующих версиях |
<a id="lib/Model/Payout/PayoutCancellationDetailsPartyCode.php"></a>
#### [lib/Model/Payout/PayoutCancellationDetailsPartyCode.php](../../lib/Model/Payout/PayoutCancellationDetailsPartyCode.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 40 | \YooKassa\Model\Payout\PayoutCancellationDetailsPartyCode::MERCHANT | Будет удален в будущих версиях |
<a id="lib/Model/Receipt.php"></a>
#### [lib/Model/Receipt.php](../../lib/Model/Receipt.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 529 | \YooKassa\Model\Receipt::getPhone() | Устарел — данные рекомендуется брать в параметре receipt.customer.phone. |
| 543 | \YooKassa\Model\Receipt::setPhone() | Устарел — данные рекомендуется передавать в параметре receipt.customer.phone. |
| 558 | \YooKassa\Model\Receipt::getEmail() | Устарел — данные рекомендуется брать в параметре receipt.customer.email. |
| 572 | \YooKassa\Model\Receipt::setEmail() | Устарел — данные рекомендуется передавать в параметре receipt.customer.email. |
<a id="lib/Model/Refund.php"></a>
#### [lib/Model/Refund.php](../../lib/Model/Refund.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 383 | \YooKassa\Model\Refund::getRequestor() | Не используется. Будет удален в следующих версиях |
| 391 | \YooKassa\Model\Refund::setRequestor() | Не используется. Будет удален в следующих версиях |
<a id="lib/Model/Requestor.php"></a>
#### [lib/Model/Requestor.php](../../lib/Model/Requestor.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 51 | \YooKassa\Model\Requestor | Не используется. Будет удален в следующих версиях |
<a id="lib/Model/RequestorInterface.php"></a>
#### [lib/Model/RequestorInterface.php](../../lib/Model/RequestorInterface.php)
| Line | Element | Description |
| ---- | ------- | ----------- |
| 40 | \YooKassa\Model\RequestorInterface | Не используется. Будет удален в следующих версиях |

---

### Top Namespaces

* [\YooKassa](../namespaces/yookassa.md)

---

### Reports
* [Errors - 0](../reports/errors.md)
* [Markers - 1](../reports/markers.md)
* [Deprecated - 25](../reports/deprecated.md)

---

This document was automatically generated from source code comments on 2023-04-06 using [phpDocumentor](http://www.phpdoc.org/)

&copy; 2023 YooMoney