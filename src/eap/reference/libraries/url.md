---
summary: The OutSystems URL library provides actions to manipulate URLs, such as decoding them to text format or retrieving the URL host.
tags: 
locale: en-us
guid: 0e709970-e4e6-4adb-9fa1-1b00fc851368
app_type: mobile apps, reactive web apps
---
# URL

The OutSystems URL library provides actions to manipulate URLs, such as decoding them to text format or retrieving the URL host.

## Actions

### DecodeURL { #DecodeURL }
Converts a string that has been encoded for transmission in a URL into a decoded text value.

_Inputs_

URL : mandatory; data type Text         

The string to be decoded.

_Outputs_

DecodedText; data type Text

The decoded text.

### GetURLProtocol { #GetURLProtocol }
Returns the protocol of the given URL.

_Inputs_     

URL: mandatory; data type Text    

The URL to extract the protocol from.

_Outputs_

Protocol; data type Text

The protocol of the given URL.

### GetURLHost { #GetURLHost }
Returns the host of the given URL.

_Inputs_     

URL: mandatory; data type Text    

The URL to extract the host from.

_Outputs_

Host; data type Text

The host of the given URL.

### IsURLRelative { #IsURLRelative }
Returns true if the given URL is a relative URL.

_Inputs_     

URL: mandatory; data type Text    

The URL to be evaluated.

_Outputs_

IsRelative; data type Boolean

True if the given URL is a relative URL.

### GetRelativeURL { #GetRelativeURL }
Returns the relative URL from the base URL.

_Inputs_     

URL: mandatory; data type Text    

The base URL to extract the relative URL from.

_Outputs_

RelativeURL; data type Text

The relative URL that was extracted.