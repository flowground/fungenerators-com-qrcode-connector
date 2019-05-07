# ![LOGO](logo.png) Fun Generators **flow**ground Connector

## Description

A generated **flow**ground connector for the Fun Generators API (version 1.5).

Generated from: https://api.apis.guru/v2/specs/fungenerators.com/qrcode/1.5/swagger.json<br/>
Generated at: 2019-05-07T17:40:47+03:00

## API Description

Fungenerators API gives access to the full set of generators available at fungenerators.com so that you can integrate them in your workflow or an app. [Click here to get details and subscribe](http://fungenerators.com/api) . Here are the individual API links:

  ## QR Code API ##
  Generate QR Code images for text, url, email , business cards etc. You can decode QR Code images and get the contents as well. The best and complete QR Code API on the cloud. [Click here to subscribe](http://fungenerators.com/api/qrcode)


## Authorization

Supported authorization schemes:
- API Key
## Actions

### Get a QR Code image for a business card aka VCARD

*Tags:* `QR Code`

#### Input Parameters
* `firstname` - _required_ - First Name
* `lastname` - _required_ - Last Name
* `middlename` - _optional_ - Middle Name
* `email` - _required_ - Email id
* `company` - _optional_ - Company Name
* `phone_work` - _optional_ - Work Phone Number
* `phone_home` - _optional_ - Home Phone Number
* `phone_cell` - _optional_ - Cell Phone Number
* `street1` - _optional_ - Street Address
* `street2` - _optional_ - Street Address 2
* `city` - _optional_ - City
* `zip` - _optional_ - Zip Code
* `state` - _optional_ - State
* `country` - _optional_ - Country
* `format` - _optional_ - Output image format. Must be one of png/eps/raw/svg

### Decode a QR Code image and return the cotents if successful

*Tags:* `QR Code`

### Get a QR Code image for an email

*Tags:* `QR Code`

#### Input Parameters
* `email` - _required_ - Email id to send the email to
* `subject` - _optional_ - Subject of the email(optional)
* `body` - _optional_ - Body of the email(optional)
* `format` - _optional_ - Output image format. Must be one of png/png/eps/raw/svg

### Get a QR Code image for a phone number

*Tags:* `QR Code`

#### Input Parameters
* `number` - _required_ - Phone Number
* `format` - _optional_ - Output image format. Must be one of png/eps/raw/svg

### Get a QR Code image for a block of raw data

*Tags:* `QR Code`

#### Input Parameters
* `rawtext` - _required_ - Raw Text value
* `format` - _optional_ - Output image format. Must be one of png/eps/raw/svg

### Get a QR Code image for a skype user

*Tags:* `QR Code`

#### Input Parameters
* `username` - _required_ - Skype User name
* `format` - _optional_ - Output image format. Must be one of png/eps/raw/svg

### Get a QR Code image for a Phone number for SMS messaging

*Tags:* `QR Code`

#### Input Parameters
* `number` - _required_ - Phone Number to SMS
* `format` - _optional_ - Output image format. Must be one of png/eps/raw/svg

### Get a QR Code image for a block of text

*Tags:* `QR Code`

#### Input Parameters
* `text` - _required_ - Text value
* `format` - _optional_ - Output image format. Must be one of png/eps/raw/svg

### Get a QR Code image for a url

*Tags:* `QR Code`

#### Input Parameters
* `url` - _required_ - URL value
* `format` - _optional_ - Output image format. Must be one of png/raw/eps/svg

## License

**flow**ground :- Telekom iPaaS / fungenerators-com-qrcode-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
