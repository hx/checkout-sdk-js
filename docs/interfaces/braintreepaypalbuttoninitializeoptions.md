[@bigcommerce/checkout-sdk](../README.md) > [BraintreePaypalButtonInitializeOptions](../interfaces/braintreepaypalbuttoninitializeoptions.md)

# BraintreePaypalButtonInitializeOptions

## Hierarchy

**BraintreePaypalButtonInitializeOptions**

## Index

### Properties

* [allowCredit](braintreepaypalbuttoninitializeoptions.md#allowcredit)
* [shippingAddress](braintreepaypalbuttoninitializeoptions.md#shippingaddress)
* [style](braintreepaypalbuttoninitializeoptions.md#style)

### Methods

* [onAuthorizeError](braintreepaypalbuttoninitializeoptions.md#onauthorizeerror)
* [onPaymentError](braintreepaypalbuttoninitializeoptions.md#onpaymenterror)

---

## Properties

<a id="allowcredit"></a>

### `<Optional>` allowCredit

**● allowCredit**: * `undefined` &#124; `false` &#124; `true`
*

___
<a id="shippingaddress"></a>

### `<Optional>` shippingAddress

**● shippingAddress**: * [Address](address.md) &#124; `null`
*

___
<a id="style"></a>

### `<Optional>` style

**● style**: *`Pick`<[PaypalButtonStyleOptions](paypalbuttonstyleoptions.md),  "layout" &#124; "size" &#124; "color" &#124; "label" &#124; "shape" &#124; "tagline" &#124; "fundingicons">*

___

## Methods

<a id="onauthorizeerror"></a>

### `<Optional>` onAuthorizeError

▸ **onAuthorizeError**(error: * [BraintreeError](braintreeerror.md) &#124; [StandardError](../classes/standarderror.md)*): `void`

**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| error |  [BraintreeError](braintreeerror.md) &#124; [StandardError](../classes/standarderror.md)|  The error object describing the failure. |

**Returns:** `void`

___
<a id="onpaymenterror"></a>

### `<Optional>` onPaymentError

▸ **onPaymentError**(error: * [BraintreeError](braintreeerror.md) &#124; [StandardError](../classes/standarderror.md)*): `void`

**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| error |  [BraintreeError](braintreeerror.md) &#124; [StandardError](../classes/standarderror.md)|  The error object describing the failure. |

**Returns:** `void`

___

