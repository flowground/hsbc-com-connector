# ![LOGO](logo.png) HSBC UK **flow**ground Connector

## Description

A generated **flow**ground connector for the HSBC UK API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/hsbc.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:42:20+03:00

## API Description



## Authorization

This API does not require authorization.

## Actions

### This API will return data about all our ATMs and is prepared to the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. It is regulated by the UK Competition and Markets Authority (CMA). Data is only available for the United Kingdom.

*Tags:* `ATMs`

### This API will return the branch details for all branches and is prepared to the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. It is regulated by the UK Competition and Markets Authority (CMA). Data is only available for the United Kingdom.

*Tags:* `Branches`

### This API will return data about all BCA productsand is prepared to the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. It is regulated by the UK Competition and Markets Authority (CMA). Data is only available for the United Kingdom.

*Tags:* `Products BCA`

### This API will return data about all commercial credit cards productsand is prepared to the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. It is regulated by the UK Competition and Markets Authority (CMA). Data is only available for the United Kingdom.

*Tags:* `Products Commercial Credit Cards`

### This API will return data about all PCA productsand is prepared to the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. It is regulated by the UK Competition and Markets Authority (CMA). Data is only available for the United Kingdom.

*Tags:* `Products PCA`

### This API will return data about all SME lending productsand is prepared to the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. It is regulated by the UK Competition and Markets Authority (CMA). Data is only available for the United Kingdom.

*Tags:* `Products SME Lending`

### This extended API will return data about all ATMs in the specified country. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `ATMs`

#### Input Parameters
* `country` - _required_ - The ISO country code e.g. &quot;GB&quot;

### This extended API will return data about all ATMs in the specified town. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `ATMs`

#### Input Parameters
* `country` - _required_ - The ISO country code e.g. &quot;GB&quot;
* `town` - _required_ - Town name, not case sensitive

### This extended API will data about all ATMs within a specified radius (1 to 10 miles) of the specified latitude and longitude. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `ATMs`

#### Input Parameters
* `latitude` - _required_ - Positive or negative decimal value in degrees. eg &quot51.50551621597067&quot
* `longitude` - _required_ - Positive or negative decimal value in degrees. eg &quot-0.0180120225995&quot
* `radius` - _required_ - Number of miles (1 to 10) as an integer. Default = 1

### This extended API will return data about all ATMs within a 5 mile radius of the specified postcode. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `ATMs`

#### Input Parameters
* `postcode` - _required_ - Letters and numerals only. No spaces or special characters. eg  &quotSW1A1AA&quot

### This extended API will return the branch details for all branches in the specified country. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `Branches`

#### Input Parameters
* `country` - _required_ - The ISO country code e.g. &quot;GB&quot;

### This extended API will return the branch details for all branches in the specified town. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `Branches`

#### Input Parameters
* `country` - _required_ - The ISO country code e.g. &quot;GB&quot;
* `town` - _required_ - Town name, not case sensitive

### This API will return the branch details for all branches within a specified radius (1 to 10 miles) of the specified latitude and longitude. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `Branches`

#### Input Parameters
* `latitude` - _required_ - Positive or negative decimal value in degrees. eg &quot51.50551621597067&quot
* `longitude` - _required_ - Positive or negative decimal value in degrees. eg &quot-0.0180120225995&quot
* `radius` - _required_ - Number of miles (1 to 10) as an integer. Default = 1

### This extended API will return the branch details for all branches within a 5 mile radius of the specified postcode. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `Branches`

#### Input Parameters
* `postcode` - _required_ - Letters and numerals only. No spaces or special characters. eg. &quotSW1A1AA&quot

### This extended API will return the branch details for a branch specified by its sort code. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `Branches`

#### Input Parameters
* `sortcode` - _required_ - 6 digit number with no spaces or special characters. eg. &quot400003&quot

### This extended API will return data about all BCA products for the specified segment. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `Products BCA`

#### Input Parameters
* `segment` - _required_ - Segment name from this list&#58; &quot;Basic&quot;, &quot;Business&quot;, &quot;General&quot;, &quot;Graduate&quot;, &quot;International&quot;, &quot;Packaged&quot;, &quot;Personal&quot;, &quot;Premium&quot;, &quot;Reward&quot;, &quot;SME&quot;, &quot;Student&quot;, &quot;YoungAdult&quot;, &quot;Youth&quot;.

### This extended API will return data about all commercial credit cards products for the specified segment. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `Products Commercial Credit Cards`

#### Input Parameters
* `segment` - _required_ - Segment name from this list&#58 &quot;Cashback&quot;, &quot;Corporate&quot;, &quot;General&quot;, &quot;Reward&quot;, &quot;SME&quot;.

### This extended API will return data about all PCA products for the specified segment. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `Products PCA`

#### Input Parameters
* `segment` - _required_ - Segment name from this list&#58; &quot;Basic&quot;, &quot;Business&quot;, &quot;General&quot;, &quot;Graduate&quot;, &quot;International&quot;, &quot;Packaged&quot;, &quot;Personal&quot;, &quot;Premium&quot;, &quot;Reward&quot;, &quot;SME&quot;, &quot;Student&quot;, &quot;YoungAdult&quot;, &quot;Youth&quot;.

### This extended API will return data about all SME lending products for the specified segment. It is based-on the Open Banking standards as defined by the Open Banking Implementation Entity (OBIE) in data dictionary version 1.2.4. The extended functionality may not fully adhere to the non-functional requirements of the regulator. Data is only available for the United Kingdom.

*Tags:* `Products SME Lending`

#### Input Parameters
* `segment` - _required_ - Segment name from this list&#58; &quot;AgricultureSector&quot;, &quot;AllSegmentsCorporate&quot;, &quot;Corporate&quot;, &quot;FixedGroup&quot;, &quot;FlexibleBusinessLoan&quot;, &quot;GovernmentScheme&quot;, &quot;NewCustomersOnly&quot;, &quot;SmallLoan&quot;, &quot;SpecialisedSector&quot;, &quot;SwitchersOnly&quot;.

## License

**flow**ground :- Telekom iPaaS / hsbc-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
